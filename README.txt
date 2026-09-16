GPS Rutas V2.2 — versión segura

ESTRUCTURA
v2/index.html = aplicación para grabar, guardar y consultar rutas.
puntos-interes/index.html = visualizador exclusivo de puntos de interés.
v2/manifest.json = manifest de la aplicación.

IMPORTANTE SOBRE LAS RUTAS YA GUARDADAS
Las rutas de V2 se almacenan en localStorage con la clave:
gps_routes_v2_mejorada

Por ello, reemplazar el archivo v2/index.html NO borra por sí mismo las rutas guardadas en el navegador, siempre que se mantenga el mismo origen (por ejemplo, https://arlelua.github.io/rutas_panecitos/).

ANTES DE ACTUALIZAR
1. Abre V2.
2. Pulsa “🛡️ Respaldar rutas”.
3. Guarda el JSON de respaldo en un lugar seguro.

DESPUÉS DE ACTUALIZAR
Si las rutas siguen apareciendo, no necesitas restaurar nada.
Si no aparecen, usa “♻️ Restaurar respaldo”. La opción permite reemplazar las actuales o agregar las del respaldo.

URL ESPERADAS
https://arlelua.github.io/rutas_panecitos/v2/
https://arlelua.github.io/rutas_panecitos/puntos-interes/
