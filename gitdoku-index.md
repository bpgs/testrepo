# Zur Arbeit mit Git

## Windows 7

### Ausgangssituation

Unter Windows ist die Windowsversion von Git installiert:

![Windowsversion Git](windows-systemsteuerung-git.jpg)

Man findet dann entsprechende Icons auf dem Desktop oder im Programmstart:

![Programmstart Git](programmstart-git.jpg)

Man kann entweder das Kommandozeilentool **Git Bash** oder das visuelle Werkzeug **Git Gui** starten. Im Folgenden geht es um **Git Gui**.

Nach dem Start von Git Gui hat man 3 Möglichkeiten:

* ein neues Projektarchiv erstellen
* ein Projektarchiv klonen
* ein Projektarchiv öffnen

![Git Gui Start](git-gui-01.JPG)

Außerdem werden frühere geöffnete Git-Projekte angezeigt.

### Projektarchiv öffnen und aktualisieren

Wir haben bereits aus früheren Aktivitäten eine Reihe von Git Projekten auf dem PC

![Vorhandene Git Projekte](vorhandene-git-projekte.JPG)

Ich öffne **testrepo**. Das Programmfrenster sieht dann ungefähr so aus:

![Vorhandene Git Projekte](git-projekt-testrepo-01.JPG)

Mit einem externen Programm ändere ich die Datei `xcxc.css`. Jetzt aktiviere ich **Letzte nachbessern**.

![Vorhandene Git Projekte](git-projekt-testrepo-02.JPG)

Jetzt wird mir angezeigt, welche Dateien geändert wurden und was geändert wurde. Unter **Abzeichnen** kann ich einen Text eingeben. Jetzt klicke ich auf **Eintragen** und dann auf **Versenden**. dann erscheint dieses Bild:

![Vorhandene Git Projekte](git-projekt-testrepo-03.JPG)

Noch einmal Klick auf **Versenden**. Fall eine Fehlermeldung erscheint, dann mit markierte Option anklicken. Im Erfolgsfall erscheint:

![Vorhandene Git Projekte](git-projekt-testrepo-04.JPG)

In der Repo unter Github sieht man dann die Änderung

![Vorhandene Git Projekte](git-projekt-testrepo-05.JPG)
