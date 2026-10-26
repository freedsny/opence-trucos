# OpenCE Halo Trucos (español)

Modificación del código oficial OpenCE `build-273` para Android.

## Cambios
- Añade **TRUCOS** directamente al menú de pausa, al lado de SETTINGS.
- Abre la pantalla de trucos desde ese acceso directo, sin entrar a Network Setup.
- Traduce al español los nombres y descripciones de siete trucos: munición infinita, cargador infinito, súper salto, modo dios, muerte de un disparo, Medusa y mochila propulsora.
- Mantiene también la pantalla de trucos dentro de Network Setup.
- Incluye un flujo de GitHub Actions para compilar el APK de Android y publicarlo en Releases cuando el flujo termine correctamente.

## Compilación
Sube estos archivos al repositorio GitHub y ejecuta **Actions → Compilar OpenCE con trucos (APK) → Run workflow**. La compilación usa el código oficial de OpenCE `build-273`. Si el flujo termina bien, el APK se publica en **Releases** y también queda como artefacto temporal de Actions.

## Importante
El ZIP contiene el parche y el flujo de compilación, no un APK ya compilado. No se debe considerar la APK terminada hasta que GitHub Actions complete sin errores.
