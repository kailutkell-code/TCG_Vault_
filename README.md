# TCG Vault Kit - Clean Android Project

Dies ist ein sauberes Android-Projekt für eine lokale TCG-Sortier-App.

## Funktionen im MVP

- Boxen/Binder anlegen und bearbeiten
- Typen: Binder, Bulk-Box, Toploader-Box, Verkaufsbox, Tauschbox, Grading, Sonstiges
- Status: Sortiert, Unsortiert, Zu prüfen, Verkauf, Tausch, Archiv
- Karten/Notizen pro Box erfassen
- Suche über Boxen, Binder, Karten, Notizen und Standorte
- Foto pro Box/Binder auswählen
- NFC-Tag lesen und zuordnen
- NFC-Tag für eine Box beschreiben
- JSON-Backup exportieren
- JSON-Backup importieren
- Lokale Datenspeicherung auf dem Gerät

## GitHub Actions APK bauen

1. Dieses Projekt in ein GitHub-Repository hochladen.
2. Wichtig: Die Ordner `.github`, `app` sowie die Dateien `settings.gradle`, `build.gradle`, `gradle.properties` müssen direkt im Hauptverzeichnis liegen.
3. In GitHub auf `Actions` klicken.
4. Workflow `Build Android APK` auswählen.
5. `Run workflow` klicken.
6. Nach erfolgreichem Build unter `Artifacts` die Datei `TCG-Vault-Kit-debug-apk` herunterladen.
7. ZIP entpacken. Darin liegt die APK.

## Wichtig

Dies ist eine Debug-APK für Tests. Für den Play Store braucht man später eine signierte Release-Version.
