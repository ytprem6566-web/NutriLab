# NutriLab Android V1 Avanzada

Android nativo sin WebView. Java + Android Views para minimizar dependencias y facilitar compilación desde Android.

## Compilación desde Android

La opción más sencilla es subir este proyecto a GitHub y ejecutar la acción incluida en `.github/workflows/android.yml`. La acción compila `assembleDebug` y publica el APK como artefacto.

También puede abrirse en Android Studio/AndroidIDE con JDK 17 y Android SDK 35.

## Incluye
- Diario, comidas y macros.
- Perfil y objetivo calórico.
- Registro manual.
- Open Food Facts por búsqueda y código de barras.
- Voz con SpeechRecognizer.
- Texto y foto con Gemini 2.5 Flash.
- Confirmación antes de agregar.
- Agua y almacenamiento local.
- Ajustes para la API de Gemini.

La clave de Gemini se guarda solo localmente en el teléfono y no debe subirse a GitHub.
