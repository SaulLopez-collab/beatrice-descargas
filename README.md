# Instaladores oficiales de Beatrice

Descarga la version mas nueva de cada plataforma (los botones de [beatrice-ia.pages.dev](https://beatrice-ia.pages.dev) apuntan aqui):

- **Windows (portable, sin instalacion):** [Beatrice-2.6.0-portable.exe](https://github.com/SaulLopez-collab/beatrice-descargas/releases/latest/download/Beatrice-2.6.0-portable.exe)
- **Android (APK, versionCode 71):** [Beatrice-MouthAndScream-2.6.1-android.apk](https://github.com/SaulLopez-collab/beatrice-descargas/releases/latest/download/Beatrice-MouthAndScream-2.6.1-android.apk)

## Verificacion (contrato D3)

Cada release publica `SHA256SUMS.txt` y un resumen por archivo. El hash vigente tambien lo
sirve `GET https://beatrice-ia.pages.dev/v1/version` (campo `artefactos.*.sha256`): la app
compara ANTES de instalar; si no coincide, avisa y borra el archivo.

Fuentes: github.com/SaulLopez-collab/beatrice (codigo, privado).
