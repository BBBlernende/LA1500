# Projekt-Dokumentation

violette
Steven Salie, Noah Meier, Ensar Yldirim, Carina Sutter

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | Besprechung was wir machen, Ideen|
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Wir machen ein Roguelike Dungeon Crawler.

Wir machen einen 2D Rogue-Artigen Dungeon-Crawler. In diesem hat es verschiedene Levels mit verschieden starken Gegnern. Wärend dem Spielen erscheinen verschiedene Items, welche eingesammelt werden können, durch die man besser überleben kann. Jeder von uns Programmiert je 2 Levels mit verschiedenen Schwierigkeitsgraden. Wir werden das Spiel in Unity machen. Wir werden uns am Anfang noch mit Unity auseinandersetzen müssen, da es noch neu für uns ist.

### 1.2 User Stories


| US-№ | Verbindlichkeit | Typ         | Beschreibung                       |
| ---- | --------------- | ----        | ---------------------------------- |
| 1    |	Muss           |	Funktional |	Als ein Spieler möchte ich, dass ein Hauptmenü angezeigt wird, damit ich mir ein Level aussuchen kann.|
| 2    |	Muss           |	Funktional |	Als ein Spieler möchte ich, dass mir das Level angezeigt wird, damit ich darauf spielen kann.|
| 3    |	Muss           |	Funktional |	Als ein Spieler möchte ich, dass es Gegner in dem Level hat, damit ich eine herausforderung habe.|
| 4    |	Muss           |	Qualität   |	Als ein Spieler möchte ich gewisse Gegner angreifen können, damit ich mehr spass als spieler habe.|
| 5    |	Muss           |	Funktional |	Als ein Spieler möchte ich sterben (ein leben verlieren) können, damit ich eine Herausforderung habe.|
| 6    |	Muss           |	Funktional |	Als ein Spieler möchte ich ein "Game Over" haben können, damit ich während dem Spiel mehr gespannt bin und eine grössere Herausforderung habe.|
| 7    |	Muss           |	Funktional |	Als ein Spieler möchte ich verschiedene Items einsammeln und verwenden können, damit ich besser überleben kann und mehr abwechslung habe.|
| 8    |	Muss           |	Funktional |	Als ein Spieler möchte ich bei beenden eines levels zum nächsten Level kommen, damit ich gleich weiterspielen kann.|
| 9    |	Muss           |	Qualität   |	Als ein Spieler möchte ich verschiedene Waffen finden und aufnehmen können, um Gegner auf unterschiedliche Weisen zu bekämpfen.|
| 10   |	Muss           |	Qualität   |	Als ein Spieler möchte ich, dass es verschiedene Arten von Gegnen in dem Spiel hat, damit es nicht langweilig wird.|
| 11   |	Kann           |	Qualität   |	Als ein Spieler möchte ich verschlossene Türen im level haben, für die ich einen Schlüssel finden muss, damit es nicht langweilig wird.|
| 12   |	Kann           |	Qualität   |	Als ein Spieler möchte ich die Waffen von getöteten Gegnern aufnehmen können, damit ich eine Motivation habe, die Gegner zu besiegen.|
| 13   |	Muss           |	Qualität   |	Als ein Spieler möchte ich ansprechende Grafik sehen, damit ich mich nicht langweile.|
| 14   |	Muss           |	Qualität   |	Als ein Spieler möchte ich ein interessant aufgebautes level haben, damit ich am spiel spass habe.|
| 15   |	Muss           |	Qualität   |	Als ein Spieler möchte ich interessante animationen sehen, damit ich mich nicht langweile.|



✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |              |         |                   |
| ...  |              |         |                   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

![MicrosoftTeams-image](https://user-images.githubusercontent.com/111045656/220883835-a667c1e0-87b9-4e81-ad2c-47e806485b6e.png)



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |  Noah Meier, Carina Sutter  | Grafik design: Level |               |
| 1.B  |       |   Noah Meier, Carina Sutter | Grafik design: Level: blöcke |               |
| 1.C  |       |   Noah Meier, Carina Sutter | Grafik design: Level: Details |               |
| 1.D  |       |   Noah Meier, Carina Sutter | Grafik design: Level: Fackel |               |
| 1.E  |       |   Noah Meier, Carina Sutter | Grafik design: Level: Moos |               |
| 1.F  |       |   Noah Meier, Carina Sutter | Grafik design: Level: Wand Grafik |               |
| 1.G  |       |   Noah Meier, Carina Sutter | Grafik design: Items |               |
| 1.H  |       |   Noah Meier, Carina Sutter | Grafik design: Coins |               |
| 1.I  |       |   Noah Meier, Carina Sutter | Grafik design: Waffe |               |
| 1.J  |       |   Noah Meier, Carina Sutter | Grafik design: Türe |               |
| 1.K  |       |   Noah Meier, Carina Sutter | Grafik design: Bagpack |               |
| 1.L  |       |   Noah Meier, Carina Sutter | Grafik design: Animation |               |
| 1.M  |       |   Noah Meier, Carina Sutter | Grafik design: Animation: Angriff |               |
| 1.N  |       |   Noah Meier, Carina Sutter | Grafik design: Animation: Items collect |               |
| 1.O  |       |   Noah Meier, Carina Sutter | Grafik design: Animation: laufen |               |
| 1.P  |       |   Noah Meier, Carina Sutter | Grafik design: Animation: stehende Animation |               |
| 1.Q  |       |   Noah Meier, Carina Sutter | Grafik design: Animation: stirbt |               |
| 1.R  |       |   Noah Meier, Carina Sutter | Grafik design: Animation: effekt Animation |               |
| 1.S  |       |   Noah Meier, Carina Sutter | Grafik design: UI: Experience |               |
| 1.T  |       |   Noah Meier, Carina Sutter | Grafik design: UI: health 0 - 100 |               |
| 1.U  |       |   Noah Meier, Carina Sutter | Grafik design: UI: Chance zum wiederbeleben 5 |               |
| 1.V  |       |   Noah Meier, Carina Sutter | Grafik design: UI: Inventar  |               |
| 1.W  |       |   Noah Meier, Carina Sutter | Grafik design: UI: Inventar: auf seite Inventar zum Waffen und Tränke aufzunehmen 3/4 slots |               |
| 1.X  |       |   Noah Meier, Carina Sutter | Grafik design: UI: Inventar: Später Bagpack aufnehmen -> 6 slots |               |
| 1.Y  |       |   Noah Meier, Carina Sutter | Grafik design: UI: Effekt |               |
| 1.Z  |       |   Noah Meier, Carina Sutter | Spiel design: 1 Spieler|               |
| 1.AA  |       |   Noah Meier, Carina Sutter | Spiel design: enemys |               |
| 1.AB |       |   Noah Meier, Carina Sutter | Spiel design: Aufbau Map|               |


Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
