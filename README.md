# Angebotsplaner

iPad-Webapp für die Beratung: Wunschbudget und Gästezahl erfassen, Pakete und Zusatzleistungen auswählen,
Kosten live berechnen, Rabatt in Prozent gewähren, AGB bestätigen, Unterschrift erfassen und das Angebot als PDF erzeugen.

- Alles steckt in `index.html` (kein Build nötig).
- Preise, Pakete, Zusatzleistungen und AGB stehen oben im Skript im Block `CONFIG`.
- Gespeicherte Angebote liegen im `localStorage` des jeweiligen Geräts.
- Das PDF wird mit jsPDF (cdnjs) erzeugt. Im Browser startet der Download direkt, in der Claude-Artifact-Ansicht läuft er über die `downloads`-Funktion.
