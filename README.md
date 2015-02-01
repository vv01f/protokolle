Protokolle der [Initiative für Freie Software und Freies Wissen Dresden](http://fsfw-dresden.de/)

### Signaturen

Die Protokolle wurden signiert um die Integrität der Angaben nachzuweisen.

#### Überprüfen der Signatur

Um die Gültigkeit einer Signatur zu überprüfen, kann man mit [GnuPG](https://www.gnupg.org/) die Datei mit dem Protokollinhalt und die Datei mit der Signatur gegeneinander abgleichen.
Darüber hinaus sollte man dem Inhaber des signierenden Schlüssels auf Basis seines "Web of Trust" vertrauen oder hinreichend genau seine Zuverlässigkeit über Dritte bestimmen können.

    $ gpg --verfify gpg --verify protokolldatei.md.asc protokolldatei.md

#### Erstellen einer Signatur

Für diejenigen, die Protokolle hier veröffentlichen, ist das Erstellen der Signatur ebenfalls einfach:

    $ gpg --output protokolldatei.md.asc --clearsign protokolldatei.md
