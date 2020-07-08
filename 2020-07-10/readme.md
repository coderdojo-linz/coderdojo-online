# 10. Juli 2020

### Überblick

| Zeit        | Thema                                                                   | Zoom-Benutzer | Zugangslink       |
| ----------- | ----------------------------------------------------------------------- | ------------- | ----------------- |
| 13:45-15:45 | [Virtuelles Elektronikbasteln](#virtuelles-elektronikbasteln)           | Zoom01        | https://us02web.zoom.us/j/87344372407?pwd=L2dvangrVVFKNm1va3RLdUhzMW5FZz09                  |
| 13:45-15:45 | [Scratch](#scratch)                                                     | Zoom02        | https://us02web.zoom.us/j/88024066954?pwd=Sy9NUlBtYnhzRXM2Y3FTSFBpd1RSZz09                  |
| 13:45-15:45 | [HTML Workshop - wir bauen eine Event-Webseite](#html-workshop---wir-bauen-eine-event-webseite)   | Zoom03        | https://us02web.zoom.us/j/82363959665?pwd=U0c0RWIxTmI2enZOaGU5OXdMN3lXUT09                  |
| 16:00-18:00 | [Asynchrone Programmierung mit C# und JavaScript](#asynchrone-programmierung-mit-c-und-javascript)| Zoom01        | https://us02web.zoom.us/j/83697366589?pwd=MXBmMWxad0NkWk93cXJQeWR6TjJDdz09        |
| 19:00-21:00 | [Dynamische Webseite mit Node.js](#dynamische-webseite-mit-nodejs)      | Zoom01        | https://us02web.zoom.us/j/87019944262?pwd=RWpGWGZaWjdqeFFNRVAraENmWm1KUT09                  |


Hinweis: Für _Zoom-Benutzer_ siehe [Erklärung](https://github.com/coderdojo-linz/coderdojo-online/blob/master/Zoom.md).


## Virtuelles Elektronikbasteln

Zeit: 13:45-15:45

### Beschreibung

Elektronikbasteln geht auch übers Internet! Mit [Tinkercad](https://www.tinkercad.com) simulieren wir Transistorschaltungen und programmieren den Arduino mit coolen Sensoren und Anzeigen. Günther und Michael freuen sich auf elektronikinteressierte AnfängerInnen und haben sich auch wieder spannende Übungen für erfahrenere Bastler einfallen lassen. AnfängerInnen **und** Fortgeschrittene sind daher willkommen!

### Voraussetzungen

Ein Computer mit [Tinkercad](https://www.tinkercad.com) Zugang.

### Mentorinnen und Mentoren

- Günther
- Michael


## HTML Workshop - wir bauen eine Event-Webseite

Zeit: 13:45-15:45

### Beschreibung

Die Trägerorganisation des CoderDojo ist der Coding Club Linz und dieser Club hat neben dem CoderDojo noch weitere Initiativen. Wir starten z.B. gerade ein Meetup (=regelmäßiges Treffen von Interessierten zum Erfahrungsaustausch und Lernen) für die neue Programmiersprache [*Rust*](https://www.rust-lang.org/). Für das Meetup brauchen wir eine Webseite. In diesem Workshop wird Karin mit euch diese Webseite bauen. Ihr könnt sehen, wie sie ein solches Projekt mit HTML und CSS angeht, dabei mithelfen und so eine Menge Tipps und Tricks für Webentwicklung lernen.

### Voraussetzungen

- grundlegendste Vorkenntnisse in HTML/CSS von Vorteil
- [Visual Studio Code](https://code.visualstudio.com)

### Mentorinnen und Mentoren

- Karin
- Rainer


## Scratch

Zeit: 13:45-15:45

### Beschreibung

Lust, euer erstes Computerspiel zu programmieren oder kennt ihr Scratch schon und wollt eure Kenntnisse aufpolieren? Dann kommt vorbei im Scratch-Workshop mit Pia und Matthias. Wir werden uns in zwei Gruppen aufteilen. Die Anfängerinnen und Anfänger lernen die Grundlagen kennen. Für alle, die schon mehr über Scratch wissen, suchen wir am Beginn des Workshops gemeinsam ein Spiel aus, an dem wir dann arbeiten.

### Voraussetzungen

- **Keine** Vorkenntnisse über Programmieren notwendig
- Software für die Teilnahme an Online CoderDojos ([Anleitung](https://linz.coderdojo.net/online-coderdojo-tipps.html))
- Installierte Version von Scratch ([Download](https://scratch.mit.edu/download))
- Online-Version von Scratch - dafür brauchst du nur einen Browser und öffnest https://scratch.mit.edu/create/

### Mentorinnen und Mentoren

- Pia
- Matthias


## Asynchrone Programmierung mit C# und JavaScript

Zeit: 16:00-18:00

### Beschreibung

Habt ihr euch schon öfter gefragt, was es mit dem *async* und *await* genau auf sich hat, das ihr in C# und JavaScript immer wieder mal seht? Ist euch noch nicht ganz klar, was der Unterschied zwischen Parallelprogrammierung und asynchroner Programmierung ist? Was sind *Promises* in JavaScript und *Tasks* in C#? In diesem Workshop erklärt euch Rainer, was es mit all diesen Dingen auf sich hat. Er wird Beispiele in JavaScript und C# zeigen, da diese beiden Sprachen in Sachen asynchroner Programmierung recht ähnlich sind, sich aber im Detail stark unterscheiden. Neugierig, wo die Unterschiede sind? Dann kommt einfach beim Workshop vorbei.

### Voraussetzungen

- Grundlegendes Wissen über JavaScript und/oder C# (eine Sprache reicht)
- [Visual Studio 2019 Community Edition](https://visualstudio.microsoft.com/downloads/)
- [Visual Studio Code](https://code.visualstudio.com)

### Mentorinnen und Mentoren

- Rainer


## Dynamische Webseite mit Node.js

Zeit: 19:00 - 21:00

### Beschreibung

Dynamischen Webseiten sind in der Lage sich Informationen zu merken und diese zu verarbeiten, weil unser Code nicht nur im Browser sondern auch am Webserver selbst ausgeführt wird. Das gibt uns Möglichkeiten, die man mit statischen Webseiten nicht hat. Dieses Mal werden wir an der Benutzerverwaltung weiterarbeiten. Noch offen sind folgende Punkte:

* die Benutzer und deren (verschlüsseltes) Passwort sollen in der Datenbank gespeichert werden
* die Clients sollten bei jedem Kommando den "Ausweis" (JWT - Json Web Token) mitschicken
* der Server soll nur Kommandos akzeptieren die einen gültigen Ausweis (JWT) mitschicken
* das Secret, das wir zum Erzeugen des "Ausweises" (JWT) benutzen, soll als Umgebungsvariable übergeben werden können

Wenn Ihr wollt, könnt Ihr Euch selbst die offenen Themen alleine oder in Gruppen ansehen und versuchen zu lösen. Wir werden uns im Workshop die Vorschläge ansehen und sie gemeinsam in unsere FeuerwehrApp übernehmen.

### Voraussetzungen

Ein Einstieg in unsere Workshop-Serie ist mit den unten erwähnten grundlegenden Kenntnissen jederzeit möglich!

#### Grundlegende Kenntnisse

- beim Programmieren (z.B. mit JavaScript, Java, C#, C++, ...)
- HTML

### Installationsanleitung

Wenn Du möchtest, kannst Du schon vorab unser Projekt bei Dir installieren. So haben wir beim Workshop mehr Zeit für's Programmieren und brauchen nicht so lange warten bis alle mit der Installation fertig sind. Eine Anleitung dazu findest Du auf [Github](https://github.com/coderdojo-neusiedl/dynamic-webpage/tree/workshop-20200710).

#### Software

- einen Texteditor wie z.B. [Notepad++](https://notepad-plus-plus.org), [Visual Studio Code](https://code.visualstudio.com)
- [Node.js](https://nodejs.org/en/download/)
- [Git](https://git-scm.com/download/win)

### Mentorinnen und Mentoren

- Thomas
