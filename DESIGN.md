# DESIGN.md — MONNÁ

Guía de marca de Monná, pastelería creativa sobre pedido en Tepotzotlán. Instagram: [@monna.mex](https://www.instagram.com/monna.mex)

**Fuentes**

| Sección | Origen |
|---|---|
| Logo, colores, tipografía, personajes | `MONNA_0001_Logo25_Presentacion_05.pdf` (Demetia by Alinea, v5, 04 mar 2025) |
| Perfil, estilo visual del feed, tono de voz, frases | Perfil de Instagram @monna.mex, leído el 2 oct 2026: bio, destacadas, cuadrícula completa y los captions de las 53 publicaciones (50 propias, 3 de cuentas colaboradoras) |
| Dirección visual de campaña | Lineamientos de la campaña en curso |

---

## 1. La marca en una línea

- **Nombre:** Monná (en captions) / MONNÁ (en títulos). Siempre con acento.
- **Categoría que usa en Instagram:** "Pastelería creativa 🎂"
- **Modelo:** "Todo sobre pedido, no contamos con tienda física 🤎✨"
- **Contacto:** WhatsApp 55 1006 3884 (enlace `wa.me` en la bio) y DM.
- **Quién habla:** dos amigas, "las pasteleras detrás de Monná".
- **Qué vende:** pasteles personalizados para eventos (bodas, XV, baby shower, infantiles), especiales de temporada, producto de línea (cheesecakes, galletas tipo NY, roles, conchas, pan de muerto, rosca) y las Cake Party (talleres de decoración).

---

## 2. Logo

- **Logotipo:** "monná" en minúsculas, trazo de pincel a mano, apilado en dos líneas (`mo` / `nná`). Es un dibujo vectorial, no una fuente: se usa siempre como imagen.
- **Versiones del PDF:** v1 con `PASTELERÍA` + `dulce & salado`; v2 sólo con `dulce & salado`. Descriptor en Taupe `#A88A77`.
- **Cómo se usa hoy en Instagram:**
  - Avatar: logotipo blanco sobre círculo Café `#784311`.
  - Etiquetas de empaque: logotipo blanco sobre círculo café y sobre círculo verde salvia.
  - Carteles de colaboración: logotipo blanco en fila con los logos aliados (sabbia · monná · Central 22; monná × Meilė).
  - Destacadas: el personaje Pastel en línea café sobre círculo blanco.
- **No hacer:** reescribirlo con una fuente manuscrita, deformarlo, ponerle sombra o contorno, usarlo en café sobre Malva o Taupe (va en blanco).

---

## 3. Colores

Hex tomados de los rellenos del PDF de marca. Para impresión manda el Pantone.

| Nombre | Pantone | HEX | RGB | Rol |
|---|---|---|---|---|
| Café Monná | 731 C | `#784311` | 120, 67, 17 | Logotipo, personajes, texto, fondo del avatar |
| Taupe | 7568 C al 65% | `#A88A77` | 168, 138, 119 | Descriptor del logo; fondo de carteles y de foto de producto |
| Salvia | 5783 C | `#A4AA84` | 164, 170, 132 | Etiquetas de empaque, fondos, acentos |
| Rosa pálido | 7604 C | `#E6D5D4` | 230, 213, 212 | Fondo claro (cartel de la primera Cake Party) |
| Malva | 7646 C | `#A96E87` | 169, 110, 135 | Acento. No aparece todavía en el feed |

**Texto sobre color (contraste WCAG)**

| Texto | Fondo | Contraste | Uso |
|---|---|---|---|
| Café / Blanco | Blanco / Café | 8.0 | Cualquier tamaño |
| Café | Rosa pálido | 5.7 | Cualquier tamaño |
| Blanco | Malva | 4.0 | Sólo títulos grandes |
| Café | Salvia | 3.3 | Sólo títulos grandes |
| Blanco | Taupe | 3.2 | Sólo títulos grandes |
| Café sobre Taupe o Malva; blanco sobre Salvia | | < 2.6 | Evitar |

**Fuera de paleta, visto en el feed:** amarillo pálido en textos ("WTF es un pastel aburrido", portadas de reels). Decidir si se adopta como sexto color o se sustituye por blanco o rosa pálido.

```css
:root {
  --monna-cafe:   #784311;
  --monna-taupe:  #A88A77;
  --monna-salvia: #A4AA84;
  --monna-rosa:   #E6D5D4;
  --monna-malva:  #A96E87;
}
```

---

## 4. Tipografía

**Oficial (PDF)**

| Nivel | Fuente | Uso |
|---|---|---|
| Logotipo | Lettering a mano (sin fuente) | Sólo el logo |
| Secundaria | Frutiger LT Pro Light | `PASTELERÍA`, `dulce & salado`, textos |

**Lo que se usa hoy en el feed (no coincide con el PDF)**

| Pieza | Estilo de letra |
|---|---|
| Cartel Cake Party 2 (ago 2026) | Serif condensada de alto contraste, blanca sobre taupe |
| "15 de Septiembre" | Caligráfica script blanca |
| "WTF es un pastel aburrido" | Serif display ancha, amarillo pálido |
| Portadas de reels | Sans redonda gruesa con contorno |
| Cartel Cake Party 1 (abr 2026) | Sans condensada extra gruesa, café sobre rosa pálido |

Frutiger no aparece en ninguna publicación y hay cinco estilos de título distintos. **Recomendación:** fijar una sola fuente de títulos (la serif condensada del cartel de agosto es la que mejor convive con el logotipo) y una sola de texto, y cargarlas en el kit de marca de Canva. Los nombres exactos de esas fuentes hay que tomarlos del archivo de Canva; desde Instagram no se pueden identificar con certeza.

---

## 5. Personajes

Cinco bocetos a mano en línea café, sin relleno: **Concha**, **Muffin** (con alitas y aureola), **Pastel** (con vela), **Sandwich** y **Carrito**.

- Hoy sólo se usa Pastel, en las portadas de destacadas. No aparecen en ninguna publicación del feed.
- Uso: café sobre fondo claro o blanco sobre fondo oscuro; sin rellenos ni redibujos en estilo plano. Acompañan, no sustituyen al logo.

---

## 6. Estilo visual

**Lo que hay hoy en el feed**

- Formato vertical 4:5; la mayoría son carruseles. Dos reels en cuadrícula.
- La fotografía manda: el pastel ocupa casi todo el cuadro. Las piezas con texto son minoría (carteles de Cake Party, fechas patrias, portadas de reels).
- **Dos etapas de foto:**
  - Lanzamiento (jun–ago 2025): primeros planos oscuros, luz cálida y dorada, fondo café o negro.
  - Desde finales de 2025: luz natural, fondos claros o neutros (gris, crema, taupe), y pasteles de evento fotografiados en jardín o venue.
- **Flores naturales** como sello: gerberas, anturios, tulipanes, orquídeas, pensamientos sobre el pastel.
- Apoyos recurrentes: platos de barro, bases de madera, velas largas, listones.
- Personas: las fundadoras en la publicación fijada de aniversario; asistentes en las Cake Party.
- Publicación de lanzamiento en blanco y negro (teaser con periódicos), única en ese estilo.

**Dirección de campaña**

- Piezas que se vean hechas a mano en Canva: elementos algo rotados, trazos y flechas dibujados, recortes irregulares; nada demasiado perfecto ni plano.
- Foto de producto sobre fondo sólido Taupe `#A88A77`.
- Fondos sólidos de la paleta, sin degradados; un mensaje por pieza.
- Traer a los personajes y el trazo de pincel al feed, que hoy no están.

---

## 7. Tono de voz

- **Hablan en plural y en femenino:** "nosotras", "hagamos juntas", "gracias por confiar en nosotras".
- **Tuteo para pedir, "ustedes" para anunciar:** "Agenda tu pastel" / "Les presentamos", "Les compartimos". Nunca de usted.
- **Agradecidas:** casi cada pastel de evento cierra dando las gracias a quien lo encargó.
- **Emotivas pero breves:** dos a cuatro líneas; los textos largos se reservan para lanzamiento y aniversario.
- **Sensoriales al describir:** suave, esponjoso, húmedo, cremoso, "crujiente por fuera y suave por dentro".
- **Juguetonas y de tendencia:** Bad Bunny y el Super Bowl, K-pop, "wtf, pero no juzgamos".
- **Espanglish ligero:** "yess pls", "It's timeeeeeeee", "stay tuned", "bestie", "deli", "birthday cake".
- **Diminutivos:** pastelito, conchitas, bizcochito, cajita, playita, compitas.
- **Locales:** Tepotzotlán en casi todos los hashtags; venues y aliados siempre etiquetados.
- **Emojis:** 🤎 es la firma (29 de 50 publicaciones) junto con ✨ (30 de 50) y 🎂. También 🙂‍↕️, 🫵🏼, 🤍 y 💐. Suelen ir al final de la frase, después del punto.

**Estructura de un caption**

1. Gancho corto o pregunta ("¿Pastel negro para tu boda? 🎂🖤").
2. Una o dos líneas de descripción o agradecimiento.
3. Llamado a agendar.
4. Créditos: `Flores: @…`, `📸: @…`, `Cake toppers: @…`.
5. De 3 a 5 hashtags.

**Estructura de un especial de temporada**

Título con emoji → lista con `•` (producto, sabores, precio) → `📅 Agenda hasta…` o `⏰ Último día para agendar:` → `🚚 Entregas:` → `📩 Envíanos DM para apartar el tuyo`.

---

## 8. Frases que uso

**Llamados a la acción**

- "Agenda tu pastel personalizado para cualquier tipo de evento"
- "Agenda tu pedido ya!"
- "Agenda por dm o vía WhatsApp 55 1006 3884"
- "Cotizaciones por dm o WhatsApp"
- "Envíanos DM para apartar el tuyo"
- "Reserva por DM para asegurar tu lugar"
- "Pregunta por disponibilidad 🤎"
- "¡Aparten el suyo con tiempo!"
- "Cupo limitado" / "¡Cupos limitados!"
- "Disponible en presentación para 10 personas, pídelo YA"
- "Disponible a partir del…" / "Disponibles del… al…"
- "Detalles en historias"

**Agradecimiento**

- "Gracias por elegirnos para sus momentos especiales"
- "Muchas gracias por hacernos parte de sus momentos especiales"
- "Gracias por confiar en nosotras"
- "Muchas gracias por la confianza"
- "Gracias por elegir a Monná para acompañarte en tus momentos más especiales"

**Presentar y describir**

- "Les presentamos…" / "Les compartimos un poco de lo que fue…" / "Les dejamos estas opciones…"
- "Llegó … a Monná"
- "con el toque original de Monná" / "un toque especial de Monná"
- "la combinación perfecta" / "una combinación que nunca falla"
- "¿Ya lo probaste?"
- "hecho con mucho cariño" / "un detalle hecho con amor"
- "Un apapacho de sabor"
- "endulzar tu momento especial" / "endulzar sus celebraciones"

**Frases de marca**

- "Pastelería creativa"
- "Sueña tu pastel y nosotros lo horneamos"
- "hagamos juntas un pastel tan especial como tu celebración"
- "No tienes que saber hacer pasteles, solo tener ganas de intentarlo"
- "En Monná siempre encontrarás un lugar seguro para crear, reírte, experimentar y disfrutar el proceso"
- "Cake Party"
- "Con cariño, las pasteleras detrás de Monná 🤎"

**Palabras más repetidas:** especial (16), gracias (15), agenda (14), personalizado (14), tradición o tradicional (8), momentos (6), Cake Party (6).

**Hashtags habituales:** `#tepotzotlán` · `#pastelpersonalizado` · `#pastelespersonalizados` · `#cake` · `#postres` · `#bodas` · `#cakeparty` · `#tepotzotlanpueblomagico`

---

## 9. Frases que nunca uso

Ausentes en las 50 publicaciones propias:

- **"usted"** ni trato formal.
- **"descuento", "promo", "oferta", "gratis", "sorteo", "giveaway", "barato":** no se vende por precio. El precio sólo aparece en un especial (Día de las Madres).
- **"tienda", "sucursal", "visítanos":** no hay local.
- **"clientes":** en el aniversario se habla de "la comunidad".
- **"la mejor pastelería", "los mejores pasteles":** no se califican a sí mismas; "perfecto" se dice del producto o de la combinación.
- **"link en bio".**
- **"Monna" sin acento.**
- **"repostería" en el texto** (sólo una vez como hashtag); la palabra es "pastelería".
- **"dulce & salado":** está en el logo, pero no aparece en la bio ni en ningún caption.

---

## 10. Inconsistencias a resolver

1. **Descriptor:** el logo dice "PASTELERÍA · dulce & salado"; Instagram dice "Pastelería creativa". Elegir uno como oficial.
2. **Portada del PDF:** dice "Restaurante MONNÁ", pero la marca no tiene local.
3. **Tipografía:** cinco estilos de título en el feed y ninguno es Frutiger (ver sección 4).
4. **Hashtag de lugar:** escrito de cinco formas (`#tepotzotlán` 18 veces, `#tepotzotlan` 8, `#tepotzotlanpueblomagico`, `#tepotzotlanpueblomágico`, `#tepozotlán`). Fijar `#tepotzotlán`.
5. **Género:** "nosotras" seis veces y "nosotros" una ("Sueña tu pastel y nosotros lo horneamos").
6. **Versión del logo:** el PDF no indica si quedó aprobada la 1 o la 2.
7. **Malva y personajes:** definidos en la identidad y sin uso en el feed.
