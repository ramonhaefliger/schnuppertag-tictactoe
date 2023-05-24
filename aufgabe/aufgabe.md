# Tic-Tac-Toe mit HTML, CSS und JavaScript

An diesem Schnuppertag ist das Ziel, ein Tic-Tac-Toe zu programmieren, dass man zu zweit auf einem Gerät spielen kann.
Mit HTML und CSS kann das Spielfeld mit den 9 Feldern erstellt und designt werden. Mit JavaScript wird dann die ganze Logik und
Funktion des Spiels erstellt. Am besten verwendest du für das CSS und JavaScript separate Dateien.

Für das CSS kannst du die folgenden Codezeile in den `<head>` Tag einfügen und den Dateinamen anpassen:
`<link rel="stylesheet" href="dateiname.css">`

Für das JavaScript kannst du die folgenden Codezeile zu unterst in den `<body>` Tag einfügen und den Dateinamen anpassen:
`<script src="dateiname.js"></script>`

Im Ordner "umsetzung" kannst du die Dateien hinterlegen. Für das Programmieren kannst du natürlich jederzeit mich fragen oder auch Google benutzen.
**Aber bitte ohne ChatGPT ;)**

Bei dieser Aufgabe kannst du kreativ sein und selber entscheiden, wie du die Webseite und das Spiel designen willst.


## Spielfeld
Für das Spielfeld kannst du zum Beispiel eine [HTML Tabelle](https://www.w3schools.com/tags/tag_table.asp),
oder einen [Grid-Container](https://www.w3schools.com/css/css_grid_container.asp) verwenden. Die Tabelle ist die einfachere Variante.

## Spiellogik
Wenn du hier angekommen bist, kannst du gerne mich um Hilfe bitten, denn jetzt wird es eher kompliziert. Vorhin hast du das Spielfeld erstellt.
Jetzt möchten wir erreichen, dass das Spiel auch funktioniert.

Dabei sollen folgende Dinge beachtet werden (diese gelten auch bei einem normalen Tic-Tac-Toe):
+ Je nachdem welcher Spieler am Zug ist, wird abwechslungsweise entweder X oder O verwendet.
+ Wenn ein Feld angeklickt wird, soll dort ein X oder O erscheinen, je nachdem welcher Spieler geklickt hat.
+ Wenn ein Feld schon gefüllt ist, sollte man es nicht erneut anklicken können.
+ Sobald drei X oder O in einer Reihe, Spalte oder diagonal sind, hat der jeweilige Spieler gewonnen.
+ Bei einem Gewinn soll eine Nachricht ausgegeben werden und das Spielfeld geleert werden.
