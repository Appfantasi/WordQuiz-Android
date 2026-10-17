WORDQUIZ ANDROID - PROGETTO DI PARTENZA

Questo progetto contiene la tua app HTML dentro www/index.html e la configurazione Capacitor.
Il workflow GitHub Actions può compilare un APK di prova senza usare Android Studio sul tuo telefono.

PASSAGGI GENERALI
1. Estrai questo ZIP.
2. Crea un repository GitHub e carica TUTTI i file e le cartelle estratte (inclusa .github/workflows/android.yml).
3. Apri la scheda Actions del repository e abilita le Actions se richiesto.
4. Avvia il workflow "Build WordQuiz Android APK" con Run workflow.
5. Quando termina correttamente, apri la sua esecuzione e scarica l'artifact "WordQuiz-debug-APK".
6. Estrai l'artifact ZIP sul telefono e apri app-debug.apk per installarlo. Android potrebbe chiedere di consentire l'installazione da quella fonte.

NOTE IMPORTANTI
- È un APK debug per installazione personale, non una versione firmata per Play Store.
- Il database locale e le funzioni multimediali vanno provati sul dispositivo. Prima di usare dati importanti, fai un backup da WordQuiz.
- Non condividere backup che contengano contenuti privati.
