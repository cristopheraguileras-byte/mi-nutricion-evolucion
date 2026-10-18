# Mi Nutrición — proyecto Android APK

Este proyecto envuelve la PWA en una aplicación Android usando Capacitor y compila un APK de prueba mediante GitHub Actions.

## Obtener el APK
1. Crea un repositorio en GitHub y sube todos los archivos de esta carpeta (incluida `.github/workflows/build-apk.yml`).
2. Abre la pestaña **Actions** del repositorio.
3. Selecciona **Construir APK Android** y pulsa **Run workflow** (o espera a que termine la compilación iniciada al subir a `main`).
4. Abre la ejecución terminada y descarga el artefacto **Mi-Nutricion-APK**.
5. Descomprime el artefacto en tu teléfono Android y abre `app-debug.apk`. Puede que Android te solicite autorizar la instalación desde esa fuente.

## Importante
- Este flujo produce un APK de depuración instalable para pruebas; no es un APK de publicación firmado para Play Store.
- Los datos de la app se guardan localmente en el dispositivo. No hay sincronización en la nube.
- Los valores nutricionales del prototipo son los valores por porción transcritos de las tablas de referencia y no reemplazan la validación de tu nutricionista.
- Si actualizas los archivos dentro de `www/`, vuelve a ejecutar el workflow para generar un APK nuevo.
