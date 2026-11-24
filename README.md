# Vibe Check

**Zwei Hefte für Apps, die du mit KI baust: erst prüfen, dann besser bauen.**
Aus dem Vibe Coding Lab im CULTRA Brühl (12.12.2026).

| | Teil | Heft | Wofür |
|---|---|---|---|
| 1 | **Break It** | [Vibecoding-Checkliste](vibecoding-checkliste.pdf) · PDF, 31 Seiten | Prüfen, was du gebaut hast. |
| 2 | **Build It** | [Vibecoding-Baukasten](vibecoding-baukasten.pdf) · PDF, 23 Seiten | So bauen, dass von Anfang an weniger kaputtgeht. |

In beiden PDFs lassen sich die Kästchen anklicken. Speichern nicht vergessen.

## 1 · Break It: die Vibecoding-Checkliste

**[Vibecoding-Checkliste öffnen (PDF, 31 Seiten)](vibecoding-checkliste.pdf)**

Am Handy geht es so am schnellsten: [direkt herunterladen](https://github.com/Maybe4a6f7365/vibe-check/raw/main/vibecoding-checkliste.pdf).

Drin stehen: die vier Fragen mit Tests zum Selbermachen, die OWASP Top 10 als Maßstab, der Fix-Kreislauf, Sätze an die KI und Quellen zum Weiterlernen.

### Die vier Fragen

Mit vier Fragen kannst du jede App prüfen. Frage 1 kommt immer zuerst: Sie entscheidet, wie gründlich der Rest sein muss.

| | Frage | Regel beim Bauen |
|---|---|---|
| 1 | **Was ist hier wertvoll?** | Nur sammeln, was die App wirklich braucht. Limits für alles, was Geld kostet. |
| 2 | **Was liegt offen herum?** | Schlüssel in `.env`. Die Datei wird nie mitgespeichert (`.gitignore`). Einmal draußen: sperren und neu erzeugen. |
| 3 | **Wem glaubt die App?** | Der Server entscheidet. Eingaben sind nur Text. |
| 4 | **Wer darf was?** | Login nicht selbst bauen. Mit Datenbank: Zugriffsregeln einschalten. |

## 2 · Build It: der Vibecoding-Baukasten

**[Vibecoding-Baukasten öffnen (PDF, 23 Seiten)](vibecoding-baukasten.pdf)**

Am Handy geht es so am schnellsten: [direkt herunterladen](https://github.com/Maybe4a6f7365/vibe-check/raw/main/vibecoding-baukasten.pdf).

Drin stehen: sechs Bausteine mit Vorlagen zum Kopieren, Sätzen an die KI und Quellen zum Weiterlernen.

| | Baustein | Worum es geht |
|---|---|---|
| 1 | **Bauplan: die Spec** | Erst aufschreiben, was gebaut wird und was nie passieren darf. Mit Vorlage `spec.md`. |
| 2 | **Leitplanken: AGENTS.md** | Regeln, die dein Agent bei jedem Start liest. Mit Vorlage. |
| 3 | **Speicherstände: Git** | Probebaustelle, kleine Commits, der Weg zurück. |
| 4 | **Abnahme im Netz: GitHub** | Vorlegen, prüfen, einbauen: der Pull Request. |
| 5 | **Prüfstraße: Tests** | Tests vor dem Code, selbst starten, Sonderfälle nicht vergessen. |
| 6 | **Qualität** | Fertig heißt geprüft. |

### Der Ablauf

Spec → Plan prüfen → klein bauen → Tests → Checkpoint. Und wieder von vorn.

1. Erst der Plan, dann der Bau.
2. Die KI baut. Du entscheidest.
3. Fertig ist, was geprüft ist.

## Bevor du etwas veröffentlichst

- [ ] Alle Tests sind grün.
- [ ] Keine Schlüssel im Code. Sie liegen in `.env`.
- [ ] Die vier Fragen sind geprüft.
- [ ] Ich kann jede Änderung erklären.
- [ ] Checkpoint ist gesetzt.

## Hausordnung

Mit Erlaubnis ist Hacken ein Beruf. Ohne Erlaubnis ist es eine Straftat.
Teste nur deine eigene App. Fremde Apps nur mit schriftlicher Erlaubnis.
