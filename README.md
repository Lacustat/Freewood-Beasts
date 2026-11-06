# Freewood-Beasts

**Deutsch & English · German & English.** Autor · Author: Lacustat. Version 0.6.1 · Interface 16001 (World of Warcraft: Forever).

![Beasts](https://github.com/Lacustat/Freewood-OctoWoW-Bilder/blob/main/beasts.jpg)

## Inhalt · Contents
- [Deutsch](#deutsch)
- [English](#english)
- [Tastenbelegung · Key bindings](#tastenbelegung--key-bindings)

## Deutsch

### Was ist das?
Das Archiv wilder Tiere: wo sie leben, was sie fressen, was das Zähmen lehrt. Es lernt beim Spielen, mit Export, Import und Teilen.

### Funktionen
- Ein Tier anvisieren: „Gesehen“ mit Fundort; Wildtierkunde: „Erforscht“; gezähmt: „Gezähmt“ mit den Fähigkeiten, damit Jäger wissen, wo sie welchen Rang für ihren Begleiter finden.
- Suche und Filter (Familie, Gebiet, Status), Kartenanzeige der Fundorte.
- **Fähigkeiten-Filter**: Fähigkeit wählen, dann Rang (alle Ränge mit Stufe und Anzahl Tiere) oder „ab Rang“. Mit `Freewood-BeastsData` (Petopia) kennt er alle Ränge und jedes Tier, das sie lehrt.
- **Tooltips** an jeder Fähigkeit: Zauberbeschreibung, Begleiterstufe, Trainingspunkte und lehrende Tiere. Klick zeigt die Tiere mit dieser Fähigkeit.
- Export und Import; Austausch über Gilde, Gruppe und Schlachtzug, Daten anderer Spieler überschreiben nie deine eigenen.
- Mit dem Brett lassen sich Wildtierdaten per Brief weitergeben (verschlüsselt, aber importierbar).

### Abhängigkeiten
- Benötigt: `Freewood-Core`, `Freewood-Pet`
- Optional: `Freewood-BeastsData`

### Befehle
- `/fwbeasts`: Reiter öffnen
- `/fwbeasts map`: Diagnose der Kartenanzeige

### Installation
Den Ordner `Freewood-Beasts` nach `World of Warcraft\_forever_\Interface\AddOns\` kopieren. Neue Dateien lädt das Spiel erst nach einem kompletten Neustart; ein `/reload` genügt nur, wenn sich bestehende Dateien geändert haben. Fehler sichtbar machen: `/console scriptErrors 1`, danach `/reload`.

### Hinweise
Alles Neue ist, soweit nicht anders vermerkt, im Spiel noch nicht geprüft (getestet wurde in einer Simulation).

### Lizenz
GPL-3.0, siehe `LICENSE`.

---

## English

### What is it?
The archive of wild beasts: where they live, what they eat, what taming teaches. It learns while you play, with export, import and sharing.

### Features
- Target a beast: “seen” with location; beast lore: “researched”; tamed: “tamed” with the abilities, so hunters know where to find which rank for their companion.
- Search and filters (family, zone, status), map display of locations.
- **Ability filter**: pick an ability, then a rank (every rank with level and number of beasts) or “rank and up”. With `Freewood-BeastsData` (Petopia) it knows every rank and each beast that teaches it.
- **Tooltips** on every ability: spell text, pet level, training points and teaching beasts. Click lists the beasts with that ability.
- Export and import; exchange via guild, party and raid, other players' data never overwrites your own.
- With Brett, beast data can be passed on by letter (encoded, but importable).

### Dependencies
- Required: `Freewood-Core`, `Freewood-Pet`
- Optional: `Freewood-BeastsData`

### Commands
- `/fwbeasts`: Reiter öffnen
- `/fwbeasts map`: Diagnose der Kartenanzeige

### Installation
Copy the folder `Freewood-Beasts` to `World of Warcraft\_forever_\Interface\AddOns\`. New files only load after a full game restart; a `/reload` is enough only when existing files changed. To see errors: `/console scriptErrors 1`, then `/reload`.

### Notes
Unless marked otherwise, everything new has not yet been verified in game (it was tested in a simulation).

### License
GPL-3.0, see `LICENSE`.

## Tastenbelegung · Key bindings
**DE:** Unter Optionen > Tastaturbelegung gibt es einen eigenen Abschnitt für dieses Modul. Dort lässt sich eine Taste zum Öffnen und Schließen des Reiters belegen (zum Beispiel J für die Gilde). Ist der Reiter schon offen, schließt dieselbe Taste das Fenster. Nach der Installation einmal das Spiel neu starten, damit die neue Datei Bindings.xml gelesen wird.
**EN:** Options > Key Bindings has its own section for this module. Bind a key to open and close the tab (for example J for the guild). If the tab is already open, the same key closes the window. Restart the game once after installing so the new Bindings.xml file is read.
