# Projekt-Dokumentation

violette
Steven Salie, Noah Meier, Ensar Yildirim, Carina Sutter

| Datum    | Version | Zusammenfassung                                              |
| -------- | ------- | ------------------------------------------------------------ |
| 02.03.23 | 0.0.1   | Beginn des Projektes                                       |
| 09.03.23 | 0.0.2   | Informieren über das Programmieren mit Unity und grobe planung des Spiellayouts |
| 16.03.23 | 0.0.3   | Weiter informieren über Unity und ersten Prototypen entwickeln |
| 23.03.23 | 0.0.4   | Den Prototypen ausbauen und die Präsentation vorbereiten |


## 1 Informieren

### 1.1 Ihr Projekt

Wir machen ein Rogue-artigen Dungeon Crawler.

Wir machen einen 2D Rogue-Artigen Dungeon-Crawler. In diesem hat es verschiedene Levels mit verschieden starken Gegnern. Wärend dem Spielen erscheinen verschiedene Items, welche eingesammelt werden können, durch die man besser überleben kann. Jeder von uns Programmiert je 2 Levels mit verschiedenen Schwierigkeitsgraden. Wir werden das Spiel in Unity machen. Wir werden uns am Anfang noch mit Unity auseinandersetzen müssen, da es noch neu für uns ist.

### 1.2 User Stories


| US-№ | Verbindlichkeit | Typ         | Beschreibung                       |
| ---- | --------------- | ----        | ---------------------------------- |
| 1    |	Kann           |	Funktional |	Als ein Spieler möchte ich, dass ein Hauptmenü angezeigt wird, damit ich mir ein Level aussuchen kann.|
| 2    |	Muss           |	Funktional |	Als ein Spieler möchte ich, dass mir das Level angezeigt wird, damit ich darauf spielen kann.|
| 3    |	Muss           |	Funktional |	Als ein Spieler möchte ich, dass es Gegner in dem Level hat, damit ich eine Herausforderung habe.|
| 4    |	Muss           |	Qualität   |	Als ein Spieler möchte ich gewisse Gegner angreifen können, damit ich mehr Spass als Spieler habe.|
| 5    |	Muss           |	Funktional |	Als ein Spieler möchte ich sterben (ein Leben verlieren) können, damit ich eine Herausforderung habe.|
| 6    |	Muss           |	Funktional |	Als ein Spieler möchte ich ein "Game Over" haben können, damit ich während dem Spiel mehr gespannt bin und eine grössere Herausforderung habe.|
| 7    |	Muss           |	Funktional |	Als ein Spieler möchte ich verschiedene Items einsammeln und verwenden können, damit ich besser überleben kann und mehr abwechslung habe.|
| 8    |	Muss           |	Funktional |	Als ein Spieler möchte ich bei beenden eines levels zum nächsten Level kommen, damit ich gleich weiterspielen kann.|
| 9    |	Muss           |	Qualität   |	Als ein Spieler möchte ich verschiedene Waffen finden und aufnehmen können, um Gegner auf unterschiedliche Weisen zu bekämpfen.|
| 10   |	Muss           |	Qualität   |	Als ein Spieler möchte ich, dass es verschiedene Arten von Gegnen in dem Spiel hat, damit es nicht langweilig wird.|
| 11   |	Kann           |	Qualität   |	Als ein Spieler möchte ich verschlossene Türen im level haben, für die ich einen Schlüssel finden muss, damit es nicht langweilig wird.|
| 12   |	Kann           |	Qualität   |	Als ein Spieler möchte ich die Waffen von getöteten Gegnern aufnehmen können, damit ich eine Motivation habe, die Gegner zu besiegen.|
| 13   |	Muss           |	Qualität   |	Als ein Spieler möchte ich ansprechende Grafik sehen, damit ich mich nicht langweile.|
| 14   |	Muss           |	Qualität   |	Als ein Spieler möchte ich ein interessant aufgebautes level haben, damit ich am Spiel Spass habe.|
| 15   |	Muss           |	Qualität   |	Als ein Spieler möchte ich interessante animationen sehen, damit ich mich nicht langweile.|
| 16   |  Kann           |  Qulität    | Als ein Spieler möchte ich eine Bagpack aufsammeln und dann mehr Slots haben im Inventar.|





### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Das spiel wird gestartet |keine| Das Hauptmenü wird angezeigt |
| 2.1  | Hauptmenü | ein Level wird angeklickt | das Level wird angezeigt |
| 3.1  | Hauptmenü | ein Level wird angeklickt | das Level mit Gegnern wird angezeigt |
| 3.2  | Im Level | Spieler lässt sich angreiffen von einem Gegner| die Gesundheit des Spielers sinkt|
| 4.1  | Im Level| Spieler drückt pfeiltaste in die richtung eines Gegners | Der Gegner Stirbt oder wird verletzt |
| 5.1  | Im Level | Spieler lässt sich mehrfach angreiffen von einem Gegner| die Gesundheit des Spielers sinkt auf 0 und er Stirbt|
| 6.1  | Im Level | Spieler lässt sich mehrmals töten | ein Game-Over-Screen wird angezeigt|
| 7.1  | Im Level | Spieler läuft gegen ein Item| das Item kommt in das Inventar des Spielers |
| 8.1  | Im Level | Spieler läuft gegen die "Endtüre" | Ein neues Level startet |
| 9.1  | Im Level | Spieler läuft gegen eine Waffe | die Waffe kommt in das Inventar des Spielers |
| 10.1  | Im Level | Level wurde gestartet | Es sind verschiedene Gegner sichtbar |
| 11.1  | Im Level | Spieler Läuft gegen eine verschlossene Türe | Der Spieler kann nicht durch die Türe gehen |
| 11.2  | Im Level | Spieler Läuft gegen einen Schlüssel | Der Spieler sammelt den Schlüssel ein |
| 11.3  | Im Level mit Schlüssel im inventar | Spieler Läuft gegen eine verschlossene Türe | Der Spieler kann durch die Türe gehen |
| 12.1  | Im Level, mit waffe von getötetem gegner vor Spieler | Spieler Läuft gegen die Waffe | die Waffe kommt in das Inventar |
| 16.1  | Im Level | Spieler Läuft gegen ein Backpack | das Inventar des Spielers vergrössert sich |


### 1.4 Diagramme

![MicrosoftTeams-image](https://user-images.githubusercontent.com/111045656/220883835-a667c1e0-87b9-4e81-ad2c-47e806485b6e.png)



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 14.A  | 09.03.23 |   Noah Meier | Grafik design: Level | 120 min |
| 14.B  | 09.03.23 |   Noah Meier | Grafik design: Level: blöcke | 50 min |
| 14.C  | 09.03.23 |   Noah Meier | Grafik design: Level: Details | 20 min |
| 14.D  | 09.03.23 |   Noah Meier | Grafik design: Level: Fackel | 20 min |
| 14.E  | 09.03.23 |   Noah Meier | Grafik design: Level: Moos | 20 min |
| 14.F  | 09.03.23 |   Noah Meier | Grafik design: Level: Wand Grafik | 10 min |
| 13.G  | 16.03.23 |   Noah Meier, Carina Sutter | Grafik design: Items | 120 min |
| 13.H  | 09.03.23 |   Carina Sutter | Grafik design: Coins | 30 min |
| 13.I  | 16.03.23 |   Noah Meier, Carina Sutter | Grafik design: Waffe | 120 min |
| 13.J  | 09.03.23 |   Carina Sutter | Grafik design: Türe | 20 min |
| 13.K  | 09.03.23 |   Carina Sutter | Grafik design: Bagpack | 20 min |
| 15.L  | 23.03.23 |   Noah Meier, Carina Sutter | Grafik design: Animation | 160 min |
| 15.M  | 23.03.23 |   Noah Meier, Carina Sutter | Grafik design: Animation: Angriff | 60 min |
| 15.N  | 23.03.23 |   Noah Meier, Carina Sutter | Grafik design: Animation: Items collect | 30 min |
| 15.O  | 23.03.23 |   Noah Meier, Carina Sutter | Grafik design: Animation: laufen | 30 min |
| 15.P  | 23.03.23 |   Noah Meier, Carina Sutter | Grafik design: Animation: stehende Animation | 20 min |
| 15.Q  | 23.03.23 |   Noah Meier, Carina Sutter | Grafik design: Animation: stirbt | 20 min |
| 15.R  | 23.03.23 |   Noah Meier, Carina Sutter | Grafik design: Animation: effekt Animation | 60 min |
| 16.S  | 16.03.23 |   Noah Meier, Carina Sutter | Grafik design: UI: Experience | 20 min |
| 16.T  | 16.03.23 |   Noah Meier, Carina Sutter | Grafik design: UI: health 0 - 100 | 20 min |
| 16.U  | 16.03.23 |   Noah Meier, Carina Sutter | Grafik design: UI: Chance zum wiederbeleben 5 | 20 min |
| 16.V  | 16.03.23 |   Noah Meier, Carina Sutter | Grafik design: UI: Inventar  | 30 - 60 min |
| 16.W  | 16.03.23 |   Noah Meier, Carina Sutter | Grafik design: UI: Inventar: auf seite Inventar zum Waffen und Tränke aufzunehmen 3/4 slots | 20 min |
| 13.X  | 16.03.23 |   Noah Meier, Carina Sutter | Grafik design: UI: Effekt | 40 min |
| 13.Y  | 09.03.23 |   Carina Sutter | Spiel design: 1 Spieler| 90 min |
| 13.Z  | 16.03.23 |   Noah Meier, Carina Sutter | Spiel design: enemys | 150 min |
| 13.AA | 16.03.23 |   Noah Meier, Carina Sutter | Spiel design: Aufbau Map| 60 min |
|17.AB  | 9.3.23   |   Ensar Yildirim, Steven Salie| Prototyp: Bewegen| 60 min|
| 17.AC | 16.3.23  |   Ensar Yildirim, Steven Salie| Prototyp: Waffe| 60 min|
| 17.AD | 16.3.23  |   Ensar Yildirim, Steven Salie| Prototyp: map| 60 min|
| 17.AE | 23.3.23  |   Ensar Yildirim, Steven Salie| Prototyp: items| 60 min|
| 17.AF | 23.3.23  |   Ensar Yildirim, Steven Salie| Prototyp: health bar| 60 min|
| 17.AG | 23.3.23  |   Ensar Yildirim, Steven Salie| Prototyp: health system| 90 min|
| 17.AH | 23.3.23  |   Ensar Yildirim, Steven Salie| Prototyp: Wände| 30 min|
| 17.AI | 23.3.23  |   Ensar Yildirim, Steven Salie| Prototyp: Spieler| 60 min|
| 17.AJ | 23.3.23  |   Ensar Yildirim, Steven Salie| Prototyp: Gegner| 60 min|


## 3 Entscheiden

Wir haben uns dazu entschieden, das Projekt in unity zu programmieren.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 13.H  | 09.03.2023 | Carina Sutter | 30 min | 45 min  |
| 13.J  | 09.03.2023 | Carina Sutter | 20 min | 30 min  |
| 14.A  | 09.03.23 |   Noah Meier | 120 min | 90 min |
| 14.B  | 09.03.23 |   Noah Meier | 50 min | 60 min |
| 14.C  | 09.03.23 |   Noah Meier | 20 min | 30 min |
| 14.D  | 09.03.23 |   Noah Meier | 20 min | 20 min |
| 14.E  | 09.03.23 |   Noah Meier | 20 min | 20 min|
| 14.F  | 09.03.23 |   Noah Meier | 10 min | 20 min|
| 13.G  | 16.03.23 |   Noah Meier, Carina Sutter | 120 min | 80 min|
| 13.H  | 09.03.23 |   Carina Sutter | 30 min | 40 min|
| 13.I  | 16.03.23 |   Noah Meier, Carina Sutter | 120 min | 100 min|
| 13.J  | 09.03.23 |   Carina Sutter |  20 min | 50 min|
| 13.K  | 09.03.23 |   Carina Sutter |  20 min | 30 min|
| 15.L  | 23.03.23 |   Noah Meier, Carina Sutter | 160 min | 140 min|
| 15.P  | 23.03.23 |   Noah Meier, Carina Sutter | Grafik design: Animation: stehende Animation | 20 min | 50 min|
| 17.AB  | 9.3.23   |   Ensar Yildirim, Steven Salie| 60 min| 40 min|
| 17.AH | 23.3.23  |   Ensar Yildirim, Steven Salie| 30 min| 30 min|
| 17.AI | 23.3.23  |   Ensar Yildirim, Steven Salie| 60 min| 40 min|



## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | | | |
| 2.1  | | | |
| 3.1  | | | |
| 3.2  | | | |
| 4.1  | | | |
| 5.1  | | | |
| 6.1  | | | |
| 7.1  | | | |
| 8.1  | | | |
| 9.1  | | | |
| 10.1  | | | |
| 11.1  | | | |
| 11.2  | | | |
| 11.3  | | | |
| 12.1  | | | |
| 16.1  | | | |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
