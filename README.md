# ***Java** aktuell* Artikelvorlage im Markdown Format

## Informationen für Autoren

* Die eigentliche Vorlage befindet sich in der Datei [artikel.md](artikel.md). Alle anderen Dateien kannst du ignorieren.
* Benutze bitte keine Funktionen von Markdown, die nicht bereits in der [Vorlage](artikel.md) gezeigt werden! Vermisst du etwas, erstelle bitte einen [Issue auf GitHub](https://github.com/java-aktuell/java-aktuell-markdown-template/issues) oder nehme mit [Marcus Fihlon](mailto:marcus@fihlon.swiss) Kontakt auf.
* Wenn du zusammen mit einem oder mehreren anderen Autoren am Artikel arbeitest, so kannst du diese in Zeile 3 mit Semikolon `;` getrennt aufführen. Bitte nicht auf mehrere Zeilen verteilen!
* Wenn du möchtest, kannst du für deine Bilder ein eigenes Verzeichnis anlegen. Passe dann den Link zum Einbetten entsprechend an. Verwende immer relative Verzeichnisangaben, niemals absolute.
* Reiche deinen fertigen Artikel als Word-Datei per E-Mail bei der Redaktionsleiterin [Lisa Damerow](mailto:lisa.damerow@doag.org) ein. Bitte sende alle verwendeten Bilder separat mit (nicht in Word eingebettet). Achte darauf, dass Dateinamen und Bildreferenzen eindeutig zuordenbar sind.
* Falls es Probleme bei der Erzeugung der Word-Datei gibt oder etwas nicht wie erwartet funktioniert, kannst du dich gerne an [Marcus Fihlon](https://www.fihlon.swiss/) wenden.


## Ausgabe-Dateien generieren

Um aus einer Markdown-Datei die verschiedenen Ausgabe-Dateien (Word, PDF, HTML) zu generieren, wird das Kommandozeilen-Tool [Pandoc](https://pandoc.org/) benötigt. Die entsprechenden Aufrufe befinden sich im Shell-Skript [compile.sh](compile.sh). Das Skript konvertiert die Datei [artikel.md](artikel.md) im aktuellen Verzeichnis. Um die automatisch erzeugten Dateien wieder zu löschen, kann das Skript [clean.sh](clean.sh) aufgerufen werden.
