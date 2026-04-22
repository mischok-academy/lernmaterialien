---
{"dg-publish":true,"permalink":"/projekte/tic-tac-toe/user-story/","tags":["gardenEntry"],"dg-note-properties":{}}
---


**Als** Gelegenheitsspieler **möchte ich** ein digitales Tic-Tac-Toe-Spiel gegen einen Freund am selben Computer spielen können, **damit** wir uns ohne Stift und Papier in einem kurzen strategischen Wettkampf messen können.

## Akzeptanzkriterien

### Spielfeld & Darstellung

- Das Spiel zeigt ein **3x3-Raster** (Grid) an.
- Es gibt eine klare Anzeige, welcher Spieler (**X oder O**) gerade am Zug ist.

### Spielmechanik

- Spieler können abwechselnd auf ein leeres Feld klicken, um ihr Symbol zu setzen.
- Ein bereits besetztes Feld darf **nicht** überschrieben werden.
- Das System erkennt automatisch, wenn ein Spieler **drei Symbole** in einer Reihe (horizontal, vertikal oder diagonal) hat.

### Spielende & Ergebnis

- Sobald ein Spieler gewonnen hat, wird dies deutlich (z. B. durch eine Textmeldung "Spieler X hat gewonnen!") angezeigt.
- Wenn alle 9 Felder besetzt sind, ohne dass jemand drei in einer Reihe hat, wird das Spiel als **Unentschieden** gewertet.
- Nach Spielende muss es eine Möglichkeit geben, das Spielfeld zurückzusetzen (**Reset-Button**), um eine neue Runde zu starten.

### Validierung

- Eingaben nach Spielende (wenn bereits ein Sieger feststeht) werden ignoriert, bis das Spiel neu gestartet wird.

## Bonus (Optionale "Stretch Goals")

- _Visuelles Feedback:_ Die gewinnende Dreierreihe wird farblich hervorgehoben.
- _Scoreboard:_ Ein Zähler hält fest, wie viele Runden Spieler X und Spieler O jeweils gewonnen haben.