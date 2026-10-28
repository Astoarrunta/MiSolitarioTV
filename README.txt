SolitarioTV - Solitario Klondike (baraja espanola Fournier) para Android TV

COMPILAR
  1. Instala Android Studio y abre esta carpeta (File > Open).
  2. Espera a que termine "Gradle sync".
  3. Build > Build Bundle(s) / APK(s) > Build APK(s).
     Resultado: app/build/outputs/apk/debug/app-debug.apk
  (Por linea de comandos: ejecuta "gradle wrapper" una vez y luego "./gradlew assembleDebug")

INSTALAR EN LA TELE
  - Activa Opciones de desarrollador > Depuracion por red (o USB) en la tele.
  - adb connect IP_DE_LA_TELE:5555
  - adb install app-debug.apk
  - O copia el APK a un USB e instalalo con un explorador de archivos (Permitir fuentes desconocidas).

MANDO: cruceta = mover cursor, OK = seleccionar/colocar. OK dos veces sobre la misma carta = enviar a la base.
El juego esta en app/src/main/assets/index.html
