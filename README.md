# Wachstumsplanet V13.0.1 Final Checked

Zusätzlich behoben:
- Abenteuer-Schritte können am selben Tag nicht mehrfach gutgeschrieben werden
- zusätzliche Tagesleistung wird trotzdem als Differenz nachgetragen
- Wochenboss kann denselben Tagesfortschritt nicht mehrfach als Schaden verwenden
- Story-Auswahl vergibt nur einmal pro Tag Münzen
- alte V12-Review-Einträge ohne Antwortoptionen werden kompatibel migriert
- fehlerhafte alte Tagespläne werden sicher neu erzeugt
- Smart-Learning-Ergebnisse aktualisieren auch die Hauptstatistiken
- Klavierzeit wird nicht mehr als Lesezeit gerechnet
- neu freigeschaltete Erfolge werden gespeichert
- lastGoodSave wird innerhalb der transaktional gespeicherten Daten gesichert
- vor der Migration wird ein eigener LTS-Snapshot erstellt

Daten:
- unveränderter Chrome-Storage-Key growthPlanet
- Zusammenführung alter Daten und automatischer Backups bleibt aktiv
- V11.1-LTS-Transaktionsspeicherung, Checksum und Journal bleiben aktiv
