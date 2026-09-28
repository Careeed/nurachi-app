# Comune di Nurachi - App Android

Questa è una app Android WebView che apre il sito ufficiale:
https://www.comune.nurachi.or.it/

## Build automatica con GitHub Actions

1. Carica **tutto il contenuto di questa cartella nella radice del repository GitHub**.
2. Vai nella scheda **Actions**.
3. Seleziona **Build APK**.
4. Premi **Run workflow**.
5. Al termine apri la build completata e scarica l'artifact **Comune-Nurachi-APK**.
6. Estrai lo ZIP dell'artifact e installa `app-debug.apk` sul telefono Android.

IMPORTANTE: `.github/workflows/build-apk.yml` deve essere esattamente nella radice del repository, dentro `.github/workflows/`.
