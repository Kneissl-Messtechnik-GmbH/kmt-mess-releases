# kmt-mess-releases

Auslieferungskanal der **KMT Messsoftware**.

Dieses Verzeichnis ist öffentlich, weil der Selbstaktualisierer der Anwendung
`latest.json` und die Pakete ohne Anmeldung abrufen muss. Der Quellcode liegt
weiterhin im privaten Repository `KMT-Messsoftware`.

```
latest.json            Zeigt auf die jeweils aktuelle Fassung
releases/<version>/     Windows-Installer, macOS-DMG, Aktualisierungspakete
```

Die Dateien entstehen aus `npm run release` (Windows, in der CI) und
`npm run release:mac` (macOS, lokal). Von Hand wird hier nichts abgelegt.
