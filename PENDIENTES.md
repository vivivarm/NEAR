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
1. ~~**Filtro en el Trend Scanner (portada)**~~ ✅ hecho el 5 nov
   - Por defecto se ven los 3 sitios principales: Western Himalaya, Thar Desert, Sundarbans.
   - Filtro por lugar (chips o lista) y por tipo de pista (nieve, calor, lluvia), con opción "Ver todos".
   - Vista de tabla abajo: lugar, pista, tendencia, cambio por década, p, si es significativa, y botón "Abrir caso".
   - Los predeterminados siempre primero.
   - Al tocar un lugar en el globo, mostrar ese sitio en el scanner (además de poder abrir su caso).
2. ~~**Mensajes amables cuando falta un dato**~~ ✅ hecho el 5 nov
   - Cambiar "No snow depth at this point…" y "NASA has no usable data…" por un tono de "próximamente / en camino", sin que parezca que la NASA no tiene datos.
   - En los puntos en vivo, traer **todas** las variables que NASA POWER tenga: temperatura media, mínima y máxima, lluvia, humedad, nieve, cobertura de nieve y humedad del suelo.
   - Mensaje de la vista previa: más suave, invitando a usar el sitio publicado.
3. ✅ **Corrección de texto (hecho):** "in the Medellín" y frases parecidas en las ciudades en vivo deben quedar sin "the".
4. **Confirmar con Viviana** dónde aparece el texto de "coverage" que vio, para cambiarlo por "próximamente". Pedirle un pantallazo.
5. ✅ **Chatbase (hecho):** se subió chatbase-knowledge-ne-ar.txt con los 49 resultados reales. Ojo: el plan gratis permite solo 50 mensajes al mes; decidir antes de la competencia si se usa la prueba gratis de 7 días u otra herramienta.
6. **Mensaje en inglés para el equipo** presentando el sitio y los hallazgos de los datos.
7. ✅ **Proyecciones futuras CMIP6 (hecho el 5 nov):** datos reales de NASA NEX-GDDP-CMIP6 para los 15 lugares (temperatura y lluvia, SSP2-4.5 y SSP5-8.5, 2030–2100), en la máquina del tiempo del paso 6. Datos en `data/cmip6-projections.json`.

## Cómo publicar cambios
Editar `td/site` (archivo de trabajo), reconstruir `index.html`, conservar el bloque de Chatbase al final y hacer commit y push a `main`. GitHub Pages publica en 1–2 minutos.

## Próximos pasos hacia la competencia (14–15 nov 2026)
1. Confirmar nombres y roles del equipo para la página About.
2. Revisión del equipo: datos y estadísticas; textos finales del e-book; enlaces reales del visor AR y de la app (APK).
3. Decidir Chatbase: plan gratis (50 mensajes al mes) o prueba de 7 días cerca de la fecha.
4. Revisar los requisitos de entrega de Space Apps 2026 (página del proyecto, demo, uso de IA, datos de NASA usados).
5. Preparar la demo: video corto y presentación.
6. Pruebas en varios celulares y navegadores; congelar cambios el 13 nov.
7. Plan B para el día: copia sin internet del sitio y capturas de pantalla.
