# Game Design Document (GDD)

## Table of Contents

## 1 Überblick

## 1.1 Theme / Setting / Genre

  - **Arbeitstitel**: 2D MMORPG
  - **Theme**: ?
  - **Setting**: Mittelalter Fantasy
  - **Genre**: 2D Sandbox (teilweise Open World) MMORPG mit RPG-, Survival-, Aufbau- und Simulationsaspekten
  
## 1.2 Zusammenfassung

Bei diesem Spiel liegt der Fokus auf **PvP** und **Gathering**.\
Jeder Spieler kann 1 - 2 Characktere spielen und besitzt mindestens ein Lager (Housing), in welchem er alle seine Items aufbewahren kann.\
Auf diesen Store kann er mit all seinen Charakteren zugreifen. Der Spieler muss diesen Store allerdings während des Spieles erst bauen und kann theooretisch beliebog viele Stores errichten.\
Sein Rucksack besitzt nur eine sehr begrenzte Kapazität.\
Der entscheidende Punkt ist, dass andere Spieler diesen Store erobern können.\
Jeder Store besitzt ein gewisses Schutzlevel und je höher dieses Level, desto uneinnehmbarer wird der store.\
Je stärker der Spieler, umso größer aber auch die Chance, den Store einzunehmen.\
Allerdings muss der Spieler haufenweise Resourcen ranschaffen, um diesen Store auszubauen (Leveln soll schwierig sein).\
\
Bei "League of Legends" (R) (von Riot Games) hat jedes Team eine Base und man muss die feindliche Base erobern.\
In diesem Spiel gibt es viele Basen, denn jeder Spieler hat eine oder mehrere.\
Da der Spieler (mit viel Aufwand) aber immer wieder neue Basen bauen kann, wenn er keine mehr besitzt, kann er auch lediglich seine Items verlieren.\
\
Um die Stores besser zu schützen, sollen die Spieler auf die Idee kommen, eigene Dörfer zu gründen, wobei sie einfach mehrere Häuser in einem direkten Umkreis errichten und sich gegenseitig beim Verteidigen helfen.\
Und da man ein Dorf nicht alleine erobern kann, benötigt es ein Team (Teamplayer-Aspekt).\
\
Desweiteren soll der Spieler Bedürfnisse besitzen (Nahrung usw., Survival-Aspekt), sodass ganze Wirtschaftskeisläufe (am besten innerhalb eines Dorfes) entstehen. Hierbei soll auch viel über das Meta Gaming funktionieren.\
\
Resourcen sind überall auf der Karte verteilt, liegen aber nicht nah beieinander.\
D.h. der Spieler muss weitere Strecken laufen, um an Resourcen zu kommen, weshalb es Sinn macht, weitere Stores in der Nähe der Rohstoffquellen zu bauen, welche wiederum erobert werden können.\
\
Sobald man mit mindestens 5 Spielern ein Dorf gegründet hat, kann man außerdem Wachen (NPCs) für Gold einstellen, die das Dorf beschützen, wenn die Spieler offline sind.\
Dafür könnten die Spieler dann wieder Steuern erheben und diese wiederum in einem gemeinsamen Lagerhaus lagern (--> Goldschatz).

## 1.3 Ziel-Plattformen

Wir konzentrieren uns lediglich auf **Windows & Linux**, Mac OSX wird vorerst nicht offiziell supportet, da der Aufwand dafür zu hoch ist.\
Desweiteren werden keine mobilen Geräte (Android / iOS) unterstützt.

**Minimale Systemanforderungen**:

  - Java 8+ installiert
  - OpenJDK und OracleJDK Support
  - CPU: mindestens ein i3-3217U oder vergleichbar
  - mindestens 4GB RAM (inkl. OS --> 2GB RAM fürs Spiel)
  - 4GB freier Speicherplatz
  - GPU: OpenGL 2.0+ mit Framebuffer Extension
  - Minimale Bildschirmauflösung: 800x600 Pixel
  - Plattform: Windows 7+ (64 Bit), Linux (64 Bit) oder Mac OSX 10.10+ (inoffiziell, evtl. später)
  
## 1.4 Localization / Multi-Language

Jeder auf der Welt soll dieses Spiel spielen können, sofern er die Sprache kann und seine Plattform unterstützt wird.\
Die Systemanforderungen müssen also erfüllt sein.\
\
Folgende **Sprachen** sind geplant:

  - Deutsch (Standard)
  - Englisch
  
Beide Sprachen werden parallel entwickelt, d.h. es wird nicht erst alles Deutsch gemacht und dann ins englische übersetzt, sondern direkt Hand in Hand.

## 1.5 Zielgruppe

  - FSK 12
  - Spieler im Alter 12 - 99
  - Fantasy
  - RPG
  - 2D Pixelart
  - Indie
  - Massive Multiplayer Online Game (MMO)
  - Meta Gaming
  - Explorer / Farmer usw.
  - muss noch ergänzt werden.
  
## 1.6 Project Scope (Projekt-Umfang)

### 1.6.1 Game Time Scale

Wird später ergänzt. Das Projekt darf 2 Jahre nicht überschreiten, nach spätestens einem halben Jahr soll bereits eine kleine Dev-Preview für Beta Tester erscheinen.

### 1.6.2 Team-Größe

Wird später ergänzt.

### 1.6.3 Benötigte Lizenzen / Hardware / andere Kosten

Die Hardware besitzt jeder Entwickler selbst. Hierfür fallen keine Kosten an.
Evtl. Überlegungen:

  - Photoshop / Affinity Photo / Affinity Designer
  - [Aseprite](https://www.aseprite.org/) (für Pixel-Animationen)
      * bei der kostenlosen Version kann man nicht Speichern --> wenn dann kaufen
  - evtl. [Sprite Lamp](http://store.steampowered.com/app/316830/Sprite_Lamp/)
      * 31,99€, Pro Version: 82,99€

Diese muss der jeweilige Entwickler selbst tragen, falls keine Ausnahme durch die Projektleitung besteht.\
Für Affinity Photo & Asesprite existieren besitzen wir noch freie Lizenzen.

### 1.6.4 Totale Kosten

Steam Gebühr: 100 US-Dollar

## 1.7 Einflüsse

Die folgenden Spiele haben uns als Inspiration gedient:

  - **League of Legends**
  - World of Warcraft
  - Dark Souls
  - **Ultima Online** (the first MMO in the world)
  - The Elder Scrolls Online
  
## 1.8 Elevator Pitch

Muss noch ergänzt werden.

## 1.9 Was macht das Projekt aus? Was unterscheidet es von anderen (Alleinstellungsmerkmale)?

## 1.10 Content Updates & Mods

# 2 Gameplay

# 3 Content & Story

## 3.1 Waren

  - Nahrung
  - Futter für Tiere (?)
  - Gold (als Währungsmittel)

## 3.2 Transportmittel

### 3.2.1 Pferd

  - deutlich schneller als zu Fuß
  - mittelmäßig robust
  - einfach zu zähmen
  
### 3.2.2 Pegasus

  - schneller als Pferd
  - fliegend
  - sehr squishy
  - selten und schwierig zu zähmen
  - wenig Tragfähigkeit
  
### 3.2.3 Riesenechse

  - gerade so schnell als zu Fuß
  - Robust genug für Scharmützel
  - keine Probleme durch felsiges oder sumpfiges Terrain
  - einfach zu zähmen
  
### 3.2.4 Wyvern

  - extrem selten
  - sehr schwierig zu zähmen
  - robust
  - fliegend
  - gleich schnell wie Pferde
  - hoher Futterverbrauch
  
### 3.2.5 Kamel

  - wenig Futterverbrauch
  - Echsenlangsam
  - hohe Tragfähigkeit
  - einfach zu zähmen

# 4 Grobe Gebietsskizze

# 5 UI / HUD Design

# 6 Audio Style / Audio Design