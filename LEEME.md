# SFR · Sitio del curso «PLD/FT sin fronteras regulatorias»

Versión **v3** (23-sep-2026). Cambia la herramienta del curso: **«El levantamiento» se sustituye por «Pulso de Riesgo»**, que presenta el webinar del 23 de septiembre.

| Capítulo | Dirección | Archivo | Estado |
|---|---|---|---|
| 3 · La herramienta | `/` | `index.html` | **Pulso de Riesgo, nueva.** Tres pestañas: Por qué capacitar · Pulso de Riesgo · El taller |
| (archivo) | `/levantamiento/` | `levantamiento/index.html` | La herramienta anterior (v2), guardada. No se enlaza desde ningún lado |
| 1 · Empieza aquí | `/bienvenida/` | `bienvenida/index.html` | Actualizada: el capítulo 3 ya nombra «Pulso de Riesgo» |
| 4 · Escúchalo | `/escuchalo/` | — | **Retirado en la v3.** El texto y el audio seguían el enfoque anterior. Se rehace antes del 30-sep a partir del artículo «El curso está cumplido. ¿La empresa está preparada?» |
| 7 · Qué sigue | `/que-sigue/` | — | Ya no hace falta: la pestaña «El taller» de la herramienta cumple esa función |

## Cómo se actualiza

Sitio estático, sin compilación: se edita el archivo, se sube a GitHub (rama principal) y Netlify publica solo.

## Qué hay dentro de Pulso de Riesgo

- **Por qué capacitar:** siete temas con piezas interactivas (capacidades, líneas de defensa, roles, la norma, cumplir o blindar, 2027).
- **Pulso de Riesgo:** el líder predice y se autoevalúa; cinco personas resuelven ocho situaciones de su sector; sale un informe imprimible. Casos de actividades vulnerables tomados del Atlas de Riesgo (Maribel Vázquez Menchaca, GMC360). Casos de entidades financieras pendientes de rehacer con la fuente de Maribel.
- **El taller:** las tres sesiones, lo que se llevan, cupón automático según la fecha y ligas de inscripción.
- Las respuestas se guardan sólo en el navegador de quien la usa (localStorage, llave `pulso360_v1`).

## Quién la mantiene

**Arely Velázquez y Amanda Asaad**, en revisión alternada (Arely años impares, Amanda años pares).

---

## Historial

### v2 (22-sep-2026)

Sitio único del curso, con tres direcciones. Versión **v2** — herramienta corregida tras la auditoría normativa del 22 de septiembre de 2026.

| Capítulo | Dirección | Archivo en este repositorio | Estado |
|---|---|---|---|
| 3 · La herramienta | `/` | `index.html` | **v2, por publicar** (lo publicado hoy es la v1, con hallazgos) |
| 1 · Empieza aquí | `/bienvenida/` | `bienvenida/index.html` | Listo, **nunca se ha subido** (hoy da 404) |
| 4 · Escúchalo | `/escuchalo/` | `escuchalo/index.html` | Listo, **nunca se ha subido**; falta el mp3 en `audio/` |
| 7 · Qué sigue | `/que-sigue/` | — | **No existe.** Necesita la liga de inscripción, el precio y el cupón del taller |

Un solo sitio y no tres, para que el Qué sigue pueda leer el resultado que dejó la herramienta y para que un cambio se corrija en un solo lugar.

---

## Qué cambió de la v1 a la v2

La v1 se auditó con seis revisores independientes, uno por ordenamiento, más aritmética, coherencia interna y riesgo pedagógico. Lo corregido, por orden de gravedad:

1. **El «tercer círculo» clasificaba mal.** Ponía constructora, arrendadora y comercializadora como empresas sin obligación PLD, cuando el artículo 17 de la LFPIORPI las alcanza en sus fracciones IV, V, V Bis, VI, VII, VIII y XV. Ahora el ejemplo sólo trae empresas que no hacen ninguna actividad del artículo 17, y advierte expresamente que hay que descartarlo fracción por fracción.
2. **Faltaba el artículo 18, fracción VIII, segundo párrafo, y el 37 Bis 1 de las Reglas.** El resto del grupo no era «sana práctica»: si son filiales de propiedad mayoritaria, la Ley obliga a extenderles las políticas y las Reglas piden mecanismos centralizados de cumplimiento. Pasó de Capa N a Capa A · obligación indirecta.
3. **«Hoy no tienes obligación PLD» era falso.** Los artículos 33 Bis y 33 Ter obligan a toda sociedad mercantil a identificar y registrar a su Beneficiario Controlador, y el artículo 32 prohíbe liquidar en efectivo sobre los umbrales. Ninguna de las dos está diferida.
4. **La lectura del Transitorio Segundo estaba mal redactada.** Decía que ese párrafo «define qué se entiende por periodo anual». No sólo define: también fija el arranque, y leído solo **sí apuntaría a 2026**. Lo que gana 2027 es que el Transitorio Tercero difiere las fracciones VII a XI del artículo 18 a los plazos de las Reglas. Va ahora etiquetado como **Capa B · criterio de la casa**.
5. **Obligaciones de Actividad Vulnerable presentadas como universales.** El paso 5 y el semáforo calificaban a los bancos contra los cinco años del capacitador y los diez de resguardo, que no están en sus Disposiciones. Ahora los renglones dicen a qué régimen pertenecen.
6. **Selección de personal en bancos.** La tabla decía «no está en el capítulo de Capacitación y Difusión», que es cierto y engañoso: sí existe, en la 57ª.
7. **Nuevo ingreso, cita truncada.** Faltaba «o al inicio de sus actividades en dichas áreas», que es lo que cubre al empleado transferido de área — el caso más frecuente.
8. **No había deslinde de asesoría legal** en ninguna parte, y el único artefacto que sale del navegador —la agenda impresa— salía sin él. Ahora aparece en el perímetro, en la agenda, en el semáforo, en el pie de impresión y al cierre.
9. **Los veredictos del semáforo eran dictamen.** «Tu programa ya tiene la forma correcta» era una certificación de cumplimiento emitida sobre ocho casillas auto-declaradas. Reescritos los tres.
10. **Capítulo XII y su entrada en vigor.** Se agregó el hito del 30 de noviembre de 2026 (Transitorio Primero) y la precisión de que el 1 de enero de 2028 es el arranque del año auditado, no una fecha de entrega.
11. **Alcance declarado al inicio**, para que el corte con el taller de pago se lea como límite del material y no como carencia del lector.
12. Además: artículo 20 tercer párrafo en Capa C por no resuelto, artículo 44 (la constancia que habilita la auditoría interna), coherencia con la metodología de Riesgos, «identificación o conocimiento» del Cliente, la materia completa de los cinco años, la excepción de las veinticinco personas sin Comité, fuentes en las diez preguntas del paso 4, dos fichas nuevas, el distractor de relleno del reactivo 1, el GAFI fuera, `data-t` alineados con los títulos reales, fecha local en `localStorage` y teclado que ya no secuestra el foco.

**Lo que no se corrigió y queda abierto:** el perímetro del paso 2 sigue sin filtrar las preguntas, las fichas y el semáforo según lo que el alumno marcó. Es el trabajo que hace verdadera la promesa «mapear tu perímetro y de ahí armar tu plan», y no cabía antes del webinar.

**Lo que no se auditó:** `bienvenida/index.html` y `escuchalo/index.html`. Se revisaron sólo por búsqueda de los errores encontrados en la herramienta, y no los traen.

---

## Cómo se actualiza

Es un sitio estático, sin dependencias ni compilación.

1. Se edita el archivo directamente.
2. Se sube a GitHub (rama principal).
3. Netlify publica solo. No hay paso de build.

Todo el contenido normativo vive en el HTML, en secciones comentadas (`<!-- ==== N · NOMBRE ==== -->`). Los datos de comportamiento están en cuatro arreglos al inicio del `<script>`:

- `PREG` — las diez preguntas del levantamiento, cada una con su campo `f` de fuente.
- `FICHAS` — las siete fichas de recitar.
- `Q` — los tres reactivos.
- `CHECK` — los once renglones del semáforo.

Para cambiar un precepto citado hay que tocar tanto el texto visible como la ficha o el reactivo que lo repite. Están marcados con la clase `fte` (fuente).

---

## Quién la mantiene

**Arely Velázquez y Amanda Asaad**, en revisión alternada. Arely toma las revisiones de años impares, Amanda las de años pares, para que nunca quede sin dueño por ausencia de una sola persona.

---

## Cada cuánto debe revisarse

**Una vez al año, en enero**, y además de inmediato si se publica una reforma a la LFPIORPI, a las Reglas de Carácter General o a las Disposiciones del artículo 115 de la LIC.

La norma en la que se apoya rara vez cambia, así que la herramienta está construida para no necesitar actualización de rutina. La excepción es el calendario: 2027 es un año bisagra y las fechas se vuelven pasado.

---

## De qué depende

Si cualquiera de estos cambia, la herramienta queda incorrecta:

1. **La entrada en vigor del Acuerdo de reforma de las Reglas**, 30 de noviembre de 2026 (Transitorio Primero). Aparece en el paso 1, en la línea de tiempo y en su pie de fuente.
2. **La fecha del primer periodo anual de capacitación de Actividades Vulnerables** — 1 de enero a 31 de diciembre de 2027 (Transitorio Séptimo). Está codificada en el contador (`new Date(2027,0,1)`) y repetida en el paso 1, en la tabla del paso 3, en una ficha y en un reactivo.
3. **Las otras fechas de los transitorios** — 1 mar 2027 (Manual con metodología, Transitorio Tercero; y selección de personal, Transitorio Sexto), 1 jun 2027 (mecanismos automatizados, Noveno), 1 ene 2028 (arranque del primer año auditado, Octavo).
4. **Los cinco años de experiencia del capacitador** — Reglas, artículo 39 Bis, fracción III, «en materia de prevención de lavado de dinero y delitos relacionados a los que se refieren estas reglas».
5. **El contraste de resguardo de evidencia de capacitación: diez años contra cinco.** En Actividad Vulnerable, mínimo diez años y es obligación expresa (Reglas, artículo 39 Bis 1). En bancos, las Disposiciones no fijan plazo: los cinco años vienen de la Guía de la CNBV, apartado VI, que no es vinculante y los cuenta desde la fecha de elaboración del documento. Al editar, no convertir esos cinco años en obligación del banco, y no confundirlos con los diez años de la 59ª ni con los de la 51ª fracción XIII.
6. **El carácter no vinculante de la Guía de la CNBV de 2020** (apartado I, Objeto, cuarto párrafo) y sus horas sugeridas (20/30/20/30/40, apartado IV.5).
7. **Las disposiciones 49ª, 50ª, 43ª fr. VII, 47ª fr. VIII, 44ª último párrafo y 57ª** de las Disposiciones de Carácter General a que se refiere el artículo 115 de la Ley de Instituciones de Crédito, que sostienen toda la columna «Banco».
8. **El artículo 17 de la LFPIORPI y sus fracciones** — de él depende la clasificación del paso 2, que es el punto más atacable del material si se equivoca.
9. **El artículo 18, fracciones VIII segundo párrafo y IX**, y el **artículo 20, tercer párrafo**, que hoy va marcado como no resuelto por la norma.
10. **Los artículos 32, 33 Bis y 33 Ter**, que sostienen el cierre del perímetro cuando el alumno no marca ni banco ni Actividad Vulnerable.
11. **El artículo 37 Bis 1 y el 37 Bis fracción XI de las Reglas**, que sostienen la tarjeta del resto del grupo.
12. **El artículo 44 de las Reglas**, del que depende el argumento de la constancia que habilita a la auditoría interna.

No depende de la UMA ni de ningún valor que se actualice solo: en esta herramienta no hay montos ni conversiones.

---

## El semáforo de certeza

Tres capas, y hay que usarlas:

- **Capa A · Obligación** — está literal en la Ley, en las Reglas o en las Disposiciones.
- **Capa B · Criterio de la casa** — interpretación razonable de GMC360, no texto literal de un solo precepto. Hoy son dos: la lectura armónica de los transitorios y la conclusión sobre la inteligencia artificial.
- **Capa C · Sana práctica, no vinculante** — Guía de la CNBV, criterios de industria, y lo que la norma no resuelve.

Un material que interpreta y no lo etiqueta obliga a quien lo presenta a defender como ley lo que es criterio.

---

## La agenda se imprime

El paso 4 termina con un botón que abre el diálogo de impresión del navegador. Es `window.print()` con una hoja `@media print` que deja sólo el recuadro de la agenda **y el perímetro del paso 2**, y agrega un pie con la fecha y el deslinde. Si se agregan secciones nuevas al micrositio, revisar esa hoja para que no se cuelen en la impresión.

**Para la demostración en vivo:** ese botón abre el diálogo de impresión del sistema del presentador sobre la pantalla compartida. Conviene no demostrarlo en vivo, o compartir sólo la ventana del navegador.

---

## Lo que la herramienta guarda

Sólo en el navegador del alumno, con `localStorage`, bajo la llave `360educa_SFR_resultado`. Nunca en servidor.

```json
{
  "circulos": ["fin", "av", "otro"],
  "regimenes": 2,
  "levantamiento": { "total": 10, "faltan": 4 },
  "quiz": { "aciertos": 2, "total": 3 },
  "semaforo": { "color": "a", "n": 7, "total": 11, "fecha": "2026-09-23" }
}
```

`total` del semáforo pasó de 8 a **11** en la v2. Si el micrositio Qué sigue ya se hubiera construido contra el esquema anterior, hay que ajustarlo. La fecha se calcula en hora local, no en UTC.

El micrositio Qué sigue lee esa llave para devolverle al alumno su propio resultado. Si no la encuentra —otra computadora, otro navegador, modo privado— usa su plan B: le pregunta con un clic cómo le salió y se adapta, sin guardar nada.

Todas las lecturas y escrituras van dentro de `try/catch`.

---

## Reglas que este sitio respeta y que no se deben romper al editarlo

- **Nunca se nombra la plataforma del curso.** Ni aquí ni en ninguna pieza del alumno.
- **Todo de tú**, nunca de usted.
- **Semáforo de certeza.** Cada afirmación normativa lleva su fuente visible y su capa. Lo que viene de la Guía de la CNBV se marca siempre como sana práctica no vinculante.
- **Deslinde visible.** El material es informativo y no es asesoría legal ni dictamen. Va en el perímetro, en la agenda, en el semáforo, en el pie de impresión y al cierre.
- **El alumno no se lleva el plan.** La herramienta le devuelve su diagnóstico y su agenda para RH; el programa anual es materia del curso de pago. El alcance se declara en el paso 1, no se descubre al final.
- **Sin menú ni ligas a las otras dos páginas.** El alumno llega a cada una desde su propia lección.
- **`noindex`** en las tres páginas.
- **Paleta fija de la ruta Gratuitos:** durazno `#ffb59d` de relleno, `#d9663f` en letra, coral `#ff8361` sólo en botones. Neutros: crema `#faf5ec`, oscuro `#393e41`, negro `#1b1b1e`, gris `#4d4d4d`. Tipografía Space Grotesk para títulos, Inter para texto. Íconos en SVG, sin emojis.
