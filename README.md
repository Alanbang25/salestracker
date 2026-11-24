# Salestracker

Web-App (Standalone, läuft komplett im Browser), öffentlich nutzbar über GitHub Pages.
Änderungen am Code nur durch den Repo-Inhaber. Daten werden lokal im Browser des jeweiligen
Nutzers gespeichert (kein gemeinsames Backend — jede Person hat ihre eigene lokale Kopie).

## Spesen & Agentur (Tab „💶 Spesen“)
- Ausgaben erfassen: Datum, KW (automatisch), Ort, Anlass, Kategorie, beteiligte Personen, Kosten + Aufteilung je Person
- Agentur-Rechnung: Datum, KW, Zweck, Betrag (+ optional Rechnungs-Nr.)
- Salden: wer schuldet wie viel, Buchungsübersicht je Person, Zahlungen buchen
- Export: Excel (6 Blätter) und PDF (Druckansicht → „Als PDF speichern“) für Finanzamt/Steuerberater
- Vorlagen für Personen/Orte/Anlässe/Zwecke werden automatisch gelernt
- Daten liegen nur lokal im Browser → regelmäßig Backup (.json) ziehen
