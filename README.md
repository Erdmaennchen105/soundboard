# FriendSound – GitHub Pages + PeerJS

## Schritt für Schritt

1. Entpacke die ZIP-Datei auf deinem Computer.
2. Lege deine MP3-Dateien in den Ordner `sounds`.
3. Öffne `sounds/sounds.json` und trage deine Sounddateien ein. Beispiel:
   ```json
   [
     {"label":"Applaus","file":"applaus.mp3","emoji":"👏"},
     {"label":"Lachen","file":"lachen.mp3","emoji":"😂"}
   ]
   ```
   `file` muss exakt dem MP3-Dateinamen entsprechen. Die Beispielnamen sind Platzhalter; entsprechende MP3s musst du selbst hinzufügen.
4. Melde dich bei GitHub an und erstelle ein neues Repository, z. B. `friendsound`. Bei GitHub Free muss es für GitHub Pages in der Regel öffentlich sein.
5. Im Repository: **Add file → Upload files**. Lade alle Dateien und Ordner *innerhalb* dieses Ordners hoch, sodass `index.html` direkt im Hauptverzeichnis liegt.
6. Klicke **Commit changes**.
7. Öffne **Settings → Pages**.
8. Unter **Build and deployment → Source** wähle **Deploy from a branch**.
9. Bei **Branch** wähle `main` und `/(root)`, dann **Save**.
10. Warte einige Minuten und öffne die URL, die unter Pages angezeigt wird. Sie sieht ungefähr so aus: `https://DEIN-NUTZERNAME.github.io/friendsound/`.
11. Eine Person klickt auf **Neuen Raum starten** und teilt den Code. Alle anderen öffnen dieselbe Website, geben den Code und ihren Namen ein und klicken **Raum beitreten**.

## Wichtig
- Der Host muss die Seite geöffnet lassen. Wenn er offline geht, ist der Raum weg.
- Es wird kein Supabase verwendet. PeerJS nutzt aber einen öffentlichen Signalisierungsserver, um Browser miteinander zu verbinden. Peer-to-peer kann in manchen Netzwerken scheitern.
- Raumcodes sind keine Zugangssicherung: teile sie nur mit Freunden.
- GitHub Pages-Dateien sind öffentlich erreichbar; lade nur Sounds hoch, die du veröffentlichen darfst.
- Die Liste zeigt neue Soundereignisse live; sie wird nicht dauerhaft gespeichert und neue Teilnehmer sehen keine alten Einträge.
- Minimale Verzögerungen zwischen Geräten sind normal.

## Fehlerbehebung
- **Beitritt klappt nicht:** Prüfe Code und Host, lade neu und versuche es erneut.
- **Kein Ton:** Prüfe Dateinamen, Lautstärke und MP3. Klicke gegebenenfalls einmal selbst auf einen Sound.
- **Raumcode belegt:** Starte einen neuen Raum.
