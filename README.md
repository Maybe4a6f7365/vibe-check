# Vibe Check

**Die Vibecoding-Checkliste für Apps, die du mit KI gebaut hast.**
Aus dem Vibe Coding Lab im CULTRA Brühl (12.12.2026), zu den Teilen „Break It“ und „Build It“.

## Die Checkliste

**[Vibecoding-Checkliste öffnen (PDF, 31 Seiten)](vibecoding-checkliste.pdf)**

Am Handy geht es so am schnellsten: [direkt herunterladen](https://github.com/Maybe4a6f7365/vibe-check/raw/main/vibecoding-checkliste.pdf).
Die Kästchen lassen sich im PDF anklicken. Speichern nicht vergessen.

Drin stehen: die vier Fragen mit Tests zum Selbermachen, die OWASP Top 10 als Maßstab, der Fix-Kreislauf, Sätze an die KI und Quellen zum Weiterlernen.

## Die vier Fragen

Mit vier Fragen kannst du jede App prüfen. Frage 1 kommt immer zuerst: Sie entscheidet, wie gründlich der Rest sein muss.

| | Frage | Regel beim Bauen |
|---|---|---|
| 1 | **Was ist hier wertvoll?** | Nur sammeln, was die App wirklich braucht. Limits für alles, was Geld kostet. |
| 2 | **Was liegt offen herum?** | Schlüssel in `.env`. Die Datei wird nie mitgespeichert (`.gitignore`). Einmal draußen: sperren und neu erzeugen. |
| 3 | **Wem glaubt die App?** | Der Server entscheidet. Eingaben sind nur Text. |
| 4 | **Wer darf was?** | Login nicht selbst bauen. Mit Datenbank: Zugriffsregeln einschalten. |

## Bevor du etwas veröffentlichst

- [ ] Alle Tests sind grün.
- [ ] Keine Schlüssel im Code. Sie liegen in `.env`.
- [ ] Die vier Fragen sind geprüft.
- [ ] Ich kann jede Änderung erklären.
- [ ] Checkpoint ist gesetzt.

## Hausordnung

Mit Erlaubnis ist Hacken ein Beruf. Ohne Erlaubnis ist es eine Straftat.
Teste nur deine eigene App. Fremde Apps nur mit schriftlicher Erlaubnis.
