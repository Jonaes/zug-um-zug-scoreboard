# zug-um-zug-scoreboard
Arduino-Sketch für ein Scoreboard für das Brettspiel Zug um Zug Europa.
Die Anzeige erfolgt über ein 20x4 I2C-LCD-Display.
Nach Eingabe von Spieler und Wagenanzahl werden diese automatisch in Punkte umgerechnet.


## Vorraussetzungen/Material

* Arduino Uno
* I2C 20x4 LCD-Display
* Tastenfeld (der Code ist auf ein 4x4-Feld ausgelegt, die Buchstabentasten werden jedoch nicht genutzt)

**Verkabelung:** ![layout](https://github.com/Jonaes/zug-um-zug-scoreboard/blob/main/layout.png "Layout")

## Anleitung

0. Programm hochladen und Starten
1. Anzahl der Spieler eingeben (2-5 Spieler möglich)
2. Im Homescreen Spielernummer eingeben, um zur Punkteeingabe zu gelangen
3. Anzahl der gebauten Wagen eingeben

* Mit der Sterntaste kann die zuletzt hinzugefügte Punktezahl wieder abgezogen werden
* Mit der Rautetaste kommt man in die Endauswertung. Hier werden nacheinander die Punkte, die durch die Zielkarten addiert/subtrahiert werden müssen je Spieler abgefragt. Die Eingabe erfolgt dreistellig (evtl. mit führenden Nullen). Zuletzt wird die Spielernummer des Spielers mit der längsten Strecke eingegeben. Anschließend wird die Endplatzierung dargestellt.

## Feedback / Verbesserungsvorschläge
Immer her damit. Im Zweifel von Unwissenheit meinerseits ausgehen.

## Geplante Features
* Englische Übersetzung
* Support für weitere Zug um Zug Versionen
