# SFR · Sitio del curso «PLD/FT sin fronteras regulatorias»

Sitio único del curso, con tres direcciones. Hoy sólo existe la primera.

| Capítulo | Dirección | Estado |
|---|---|---|
| 3 · La herramienta | `/` | **Publicado** — `index.html` |
| 1 · Empieza aquí | `/bienvenida/` | Pendiente, se monta después del webinar |
| 7 · Qué sigue | `/que-sigue/` | Pendiente, se monta después del webinar |

Un solo sitio y no tres, para que el Qué sigue pueda leer el resultado que dejó la herramienta y para que un cambio se corrija en un solo lugar.

---

## Cómo se actualiza

Es un archivo estático, sin dependencias ni compilación.

1. Se edita `index.html` directamente.
2. Se sube a GitHub (rama principal).
3. Netlify publica solo. No hay paso de build.

Todo el contenido normativo vive en el HTML, en secciones comentadas (`<!-- ==== N · NOMBRE ==== -->`). Los datos de comportamiento están en tres arreglos al inicio del `<script>`:

- `PREG` — las diez preguntas del levantamiento.
- `FICHAS` — las cinco fichas de recitar.
- `Q` — los seis reactivos.
- `CHECK` — los ocho renglones del semáforo.

Para cambiar un precepto citado hay que tocar tanto el texto visible como la ficha o el reactivo que lo repite. Están marcados con la clase `fte` (fuente).

---

## Quién la mantiene

**Arely Velázquez y Amanda Asaad**, en revisión alternada. Arely toma las revisiones de años impares, Amanda las de años pares, para que nunca quede sin dueño por ausencia de una sola persona.

---

## Cada cuánto debe revisarse

**Una vez al año, en enero**, y además de inmediato si se publica una reforma a la LFPIORPI o a las Reglas de Carácter General.

La norma en la que se apoya rara vez cambia, así que la herramienta está construida para no necesitar actualización de rutina. La excepción es el calendario: 2027 es un año bisagra y las fechas se vuelven pasado.

---

## De qué depende

Si cualquiera de estos cambia, la herramienta queda incorrecta:

1. **La fecha del primer periodo anual de capacitación de Actividades Vulnerables** — 1 de enero a 31 de diciembre de 2027. Fuente: Reglas de Carácter General a que se refiere la LFPIORPI, Transitorio Séptimo del Acuerdo de 24 de julio de 2026. Está codificada en el contador (`new Date(2027,0,1)`) y repetida en el paso 1, en la tabla del paso 3, en una ficha y en un reactivo.
2. **Las otras cuatro fechas de los transitorios** — 1 mar 2027 (Manual y selección de personal), 1 jun 2027 (mecanismos automatizados), 1 ene 2028 (auditoría). Tabla del paso 1.
3. **Los cinco años de experiencia del capacitador** — Reglas, artículo 39 Bis, fracción III.
4. **Los diez años de resguardo de evidencia** — Reglas, artículo 39 Bis 1.
5. **El carácter no vinculante de la Guía de la CNBV de 2020** y sus horas sugeridas (20/30/20/30/40). Si la CNBV la sustituye por algo vinculante, cambia el argumento central del paso 5.
6. **Las disposiciones 49ª y 50ª** de las Disposiciones de Carácter General a que se refiere el artículo 115 de la Ley de Instituciones de Crédito, que sostienen toda la columna «Banco» de la tabla del paso 3.

No depende de la UMA ni de ningún valor que se actualice solo: en esta herramienta no hay montos ni conversiones.

---

## Lo que la herramienta guarda

Sólo en el navegador del alumno, con `localStorage`, bajo la llave `360educa_SFR_resultado`. Nunca en servidor.

```json
{
  "circulos": ["fin", "av", "otro"],
  "regimenes": 2,
  "levantamiento": { "total": 10, "faltan": 4 },
  "quiz": { "aciertos": 5, "total": 6 },
  "semaforo": { "color": "a", "n": 5, "total": 8, "fecha": "2026-09-23" }
}
```

El micrositio Qué sigue lee esa llave para devolverle al alumno su propio resultado. Si no la encuentra —otra computadora, otro navegador, modo privado— usa su plan B: le pregunta con un clic cómo le salió y se adapta, sin guardar nada.

Todas las lecturas y escrituras van dentro de `try/catch`: si el navegador bloquea el almacenamiento, la página funciona igual y sólo se pierde el enlace con el Qué sigue.

---

## Reglas que este sitio respeta y que no se deben romper al editarlo

- **Nunca se nombra la plataforma del curso.** Ni aquí ni en ninguna pieza del alumno.
- **Todo de tú**, nunca de usted.
- **Semáforo de certeza.** Cada afirmación normativa lleva su fuente visible. Lo que viene de la Guía de la CNBV se marca siempre como sana práctica no vinculante, nunca junto a la obligación sin distinguirlo.
- **El alumno no se lleva el plan.** La herramienta le devuelve su diagnóstico y su agenda para RH; el programa anual es materia del curso de pago.
- **Sin menú ni ligas a las otras dos páginas.** El alumno llega a cada una desde su propia lección.
- **`noindex`** en las tres páginas.
- **Paleta fija de la ruta Gratuitos:** durazno `#ffb59d` de relleno, `#d9663f` en letra, coral `#ff8361` sólo en botones. Neutros: crema `#faf5ec`, oscuro `#393e41`, negro `#1b1b1e`, gris `#4d4d4d`. Tipografía Space Grotesk para títulos, Inter para texto. Íconos en SVG, sin emojis.
