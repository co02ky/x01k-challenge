# X01k-Challenge – Installation auf dem Android-Tablet

Die App besteht aus diesem Ordner (index.html, manifest.webmanifest, sw.js, icons/, fonts/).
Damit sie auf dem Tablet installierbar ist und offline läuft, muss sie einmal über **https** erreichbar sein.
Am einfachsten und kostenlos geht das mit **GitHub Pages**. Ein claude.ai-Konto ist dafür nicht nötig.

## 1. Einmalig: Online stellen (GitHub Pages)
1. Auf github.com ein kostenloses Konto anlegen (geht am PC oder im Browser des Tablets).
2. Neues Repository anlegen, z. B. `x01k`, Sichtbarkeit **Public**.
3. „Add file → Upload files“: den **Inhalt** dieses Ordners hochladen (inkl. der Unterordner `icons` und `fonts`), dann „Commit changes“.
4. Im Repository: Settings → Pages → Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)` → Save.
5. Nach 1–2 Minuten ist die App erreichbar unter `https://<dein-name>.github.io/x01k/`.

Hinweis: Gehostet wird nur der Programmcode. Spieler, Spiele und Statistiken bleiben ausschließlich auf dem Tablet.

## 2. Auf dem Tablet installieren
1. Die Adresse in **Chrome** öffnen.
2. Chrome-Menü (⋮) → **„App installieren“** bzw. „Zum Startbildschirm hinzufügen“.
3. Ab jetzt die App über das Darts-Icon starten. Sie läuft im Vollbild und **ohne Internet**.

## 3. Updates
Geänderte Dateien im Repository ersetzen. Danach die App auf dem Tablet einmal **mit Internet** öffnen,
schließen und neu starten – dann ist die neue Version aktiv. Die Daten bleiben erhalten.

## 4. Datensicherung
Einstellungen → **Daten exportieren → Als Datei speichern** legt eine `.json`-Datei im Download-Ordner ab.
Regelmäßig sichern, besonders vor einem Tablet-Reset oder Gerätewechsel.
Wiederherstellen über Einstellungen → Daten importieren.

**Achtung:** Wer in Chrome „Websitedaten löschen“ oder die App deinstalliert, löscht auch alle Spieldaten.
