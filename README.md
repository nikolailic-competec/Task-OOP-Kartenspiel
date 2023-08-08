# Task-OOP-Kartenspiel

Aufgabe OOP - Kartenspiel

Vorbereitung:

- Richte ein neues Repository bei github ein (öffentlich, auf deinem Account, 
  Flo zu Collaborators hinzufügen)
- Arbeite mit der gewohnten Verzeichnisstruktur src/tests + kopiere die 
  build.xml + phpunit.xml.dist von einem anderen Projekt
- Arbeite mit branches (master + feature branch) und Pull Requests, sodass 
  der Pull Request für das gemeinsame Code Review verwendet werden 
  kann
  
Aufgabe:

Es soll ein einfaches Spiel (Konsolenbasiert) implementiert werden, das den 
folgenden Regeln folgt:

Jeder Spieler erhält fünf Karten, die er verdeckt vor sich auslegt. Jede Karte hat 
dabei eine andere von sechs Farben. Der Würfel zeigt keine Zahlen, sondern 
jeweils eine der sechs Farben. Es wird reihum gewürfelt. Würfelt ein Spieler eine 
Farbe, zu der er eine Karte besitzt, die noch verdeckt ist, dann dreht er diese 
Karte um. Hat ein Spieler alle Karten umgedreht, hat er gewonnen.
Am Spiel sollen die drei Spieler Alice, Bob und Carol teilnehmen.
Achte generell auf minimale Schnittstellen und auf die Einhaltung des Single-
Responsibility-Prinzips. Schreibe Unit-Tests für alle erstellten Klassen, so dass 
jeweils 100% Code Coverage erzielt wird.
Gehe in kleinen Schritten vor. Denke zunächst an "Nouns and Verbs"  und 
überlege, welche Klassen du implementieren möchtest und welche öffentlichen 
Schnittstellen diese brauchen. Arbeite dann in kleinen Schritten und schreibe 
jeweils eine Funktionalität und dann dafür die Tests.

1. Mache einen Vorschlag von Klassen und Methoden (ohne zu 
programmieren) + Besprich diese mit Flo
3. Implementiere die einfachen Klassen zuerst + Schreibe Tests dazu
Dictionary:
minimale Schnittstellen: Eine Schnittstelle soll genau/nur so viele Parameter wie 
nötig haben.
Single-Responsibility-Prinzip: https://de.wikipedia.org/wiki/Single-Responsibility-
Prinzip
„jede Klasse nur eine fest definierte Aufgabe zu erfüllen hat. In einer Klasse 
sollten lediglich Funktionen vorhanden sein, die direkt zur Erfüllung dieser 
Aufgabe beitragen“
"Nouns and Verbs"    :    Faustregel; Nomen sind Klassen, Verben sind Methoden
