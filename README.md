# 2k11-custom
Customizations of [Serendipity](https://github.com/s9y/Serendipity "Serendipity blog software") (s9y) [2k11 theme](https://github.com/s9y/Serendipity/tree/master/templates/2k11 "2k11 theme").

## Installation

+ 2k11 als Theme auswählen
+ "Bannergrafik im Kopfbereich einbinden?" auf leer setzen
+ "Globale Navigation einbinden?" auf "Nein" setzen (oder Gestaltung des Navigationsbalken selbst in user.css vornehmen)
+ Eventuell vorhandene "user.css" im Verzeichnis "/templates/2k11/" sichern bzw. umbenennen
+ Heruntergeladene "user.css" nach "/templates/2k11/user.css" kopieren
+ Datei-Berechtigungen für heruntergeladene "user.css" ggf. auf "660" setzen
+ In der neu eingespielten "/templates/2k11/user.css" im Bereich "header#banner" `background: url("/uploads/rubens-medusa_1120x644_60.jpg") no-repeat top center fixed;` die url zur gewünschten Bannergrafik eintragen.

Je nach gewünschter Größe der Bannergrafik sind noch `height: 644px;` im Abschnitt `header#banner` (für die Höhe der anzuzeigenden Bannergrafik) und `margin-top: 530px;` im Abschnitt `header > #identity` (für die Positionierung des Webseiten-Titels) anzupassen.
