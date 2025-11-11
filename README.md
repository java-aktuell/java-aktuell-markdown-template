# ***Java** aktuell* Artikelvorlage im Markdown Format

> [!WARNING]
> *Diese Vorlage ist noch im Beta-Stadium!*
>
> Bevor du sie benutzt, spreche das bitte mit Marcus Fihlon ab. Möglichkeiten zur Kontaktaufnahme:
>
> * E-Mail: [marcus@fihlon.swiss](mailto:marcus@fihlon.swiss)
> * Matrix: [@mcpringle:matrix.org](https://matrix.to/#/@mcpringle:matrix.org)
> * Mastodon: [@McPringle@fosstodon.org](https://fosstodon.org/@McPringle)
>
> *Vielen Dank!*

## Informationen für Autoren

* Die eigentliche Vorlage befindet sich in der Datei [artikel.md](artikel.md). Alle anderen Dateien kannst du ignorieren.
* Benutze bitte keine Funktionen von Markdown, die nicht bereits in der [Vorlage](artikel.md) gezeigt werden! Vermisst du etwas, erstelle bitte einen [Issue auf GitHub](https://github.com/java-aktuell/java-aktuell-markdown-template/issues) oder nehme mit [Marcus Fihlon](mailto:marcus@fihlon.swiss) Kontakt auf.
* Wenn du zusammen mit einem oder mehreren anderen Autoren am Artikel arbeitest, so kannst du diese in Zeile 3 mit Semikolon `;` getrennt aufführen. Bitte nicht auf mehrere Zeilen verteilen!
* Wenn du möchtest, kannst du für deine Bilder ein eigenes Verzeichnis anlegen. Passe dann den Link zum Einbetten entsprechend an. Verwende immer relative Verzeichnisangaben, niemals absolute.
* Vergiss nicht, beim Einreichen alle nötigen Dateien (Bilder, Quelltext, etc.) mitzuschicken. Sende dazu entweder eine ZIP-Datei per E-Mail an [Marcus Fihlon](mailto:marcus@fihlon.swiss) (Verschlüsselung per [GnuPG](https://keys.openpgp.org/search?q=marcus.fihlon%40jug.ch) möglich) oder verwende ein GitHub-Repository. Ist das GitHub-Repository privat, lade bitte [Marcus Fihlon](https://github.com/McPringle) mit entsprechenden Berechtigungen in das GitHub-Repository ein.


## Informationen für die Redaktion

### Ausgabe-Dateien generieren

Um aus einer Markdown-Datei die verschiedenen Ausgabe-Dateien (Word, PDF, HTML) zu generieren, wird das Kommandozeilen-Tool [Pandoc](https://pandoc.org/) benötigt. Die entsprechenden Aufrufe befinden sich im Shell-Skript [compile.sh](compile.sh). Das Skript konvertiert die Datei [artikel.md](artikel.md) im aktuellen Verzeichnis. Um die automatisch erzeugten Dateien wieder zu löschen, kann das Skript [clean.sh](clean.sh) aufgerufen werden.
