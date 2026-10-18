# Mi Nutrición — versión 2

Aplicación personal para registrar alimentos por equivalencias, configurar objetivos diarios, revisar progreso y guardar un respaldo local.

## Archivos
- `www/index.html`: interfaz y lógica de la app.
- `www/foods.json`: base de equivalencias transcrita del PDF de referencia.
- `capacitor.config.json`, `package.json`: configuración Android/Capacitor.
- `.github/workflows/build-apk.yml`: compilación de APK mediante GitHub Actions.

## Importante
Los valores son equivalencias de referencia del documento entregado por el usuario; no sustituyen indicaciones actuales de nutrición. La app no envía notificaciones de fondo mientras está cerrada; eso requiere integrar notificaciones locales nativas.
