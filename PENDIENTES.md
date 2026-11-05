# Pendientes: NE-AR Trend Detective (Proyecto NASA 2026)

Última actualización: 5 de noviembre de 2026

## Ya hecho (publicado en https://vivivarm.github.io/NEAR/)
- [x] Diseño estilo NASA (negro, azul y rojo NASA, letra Inter, esquinas rectas)
- [x] Logo del menú cambiado por la insignia NE-AR del chat
- [x] Chatbot "Detective NE-AR" insertado, con instrucciones nuevas, diseño e ícono
- [x] Ajustes responsive para celular
- [x] Globo: los 15 lugares con nombre y clic para abrir su caso
- [x] Globo y mapa: 20 ciudades famosas con datos en vivo de la NASA (anillos blancos)

## Por hacer (en este orden)
1. **Filtro en el Trend Scanner (portada)**
   - Por defecto se ven los 3 sitios principales: Western Himalaya, Thar Desert, Sundarbans.
   - Filtro por lugar (chips o lista) y por tipo de pista (nieve, calor, lluvia), con opción "Ver todos".
   - Vista de tabla abajo: lugar, pista, tendencia, cambio por década, p, si es significativa, y botón "Abrir caso".
   - Los predeterminados siempre primero.
   - Al tocar un lugar en el globo, mostrar ese sitio en el scanner (además de poder abrir su caso).
2. **Mensajes amables cuando falta un dato**
   - Cambiar "No snow depth at this point…" y "NASA has no usable data…" por un tono de "próximamente / en camino", sin que parezca que la NASA no tiene datos.
   - En los puntos en vivo, traer **todas** las variables que NASA POWER tenga: temperatura media, mínima y máxima, lluvia, humedad, nieve, cobertura de nieve y humedad del suelo.
   - Mensaje de la vista previa: más suave, invitando a usar el sitio publicado.
3. **Corrección de texto:** "in the Medellín" y frases parecidas en las ciudades en vivo deben quedar sin "the".
4. **Confirmar con Viviana** dónde aparece el texto de "coverage" que vio, para cambiarlo por "próximamente". Pedirle un pantallazo.
5. **Chatbase:** en Sources, agregar https://vivivarm.github.io/NEAR/ y quitar el texto viejo de Google Sites si confunde al bot.
6. **Mensaje en inglés para el equipo** presentando el sitio y los hallazgos de los datos.
7. **Proyecciones futuras CMIP6** (NEX-GDDP-CMIP6, SSP2-4.5 y SSP5-8.5) para la máquina del tiempo: paso a paso en Google Colab.

## Cómo publicar cambios
Editar `td/site` (archivo de trabajo), reconstruir `index.html`, conservar el bloque de Chatbase al final y hacer commit y push a `main`. GitHub Pages publica en 1–2 minutos.
