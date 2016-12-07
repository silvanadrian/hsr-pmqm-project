---
layout: page
title: Projektantrag
permalink: /projektantrag/
date: 2016-12-07 13:00
---

# Projektantrag für SE2 Projekt

## 1. Projektmitglieder

<table class="table">
  <thead>
    <tr>
      <th>Name</th>
      <th>E-Mail</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Silvan Adrian</td>
      <td>sadrian@hsr.ch</td>
    </tr>
    <tr>
      <td>Fabian Binna</td>
      <td>fbinna@hsr.ch</td>
    </tr>
    <tr>
      <td>Pascal Kistler</td>
      <td>p1kistler@hsr.ch</td>
    </tr>
  </tbody>
</table>

## 2. Projektbezeichnung
Entwicklung eines Spieles, das über das Netzwerk gspielt werden kann.

## 3. Beratungs- und Review-Termine
Wöchentlich zu einer dieser Zeiten:
* Do 08-09
* Do 09-10
* Do 14-15

## 4. Motivation
* Wir wollen gelerntes aus Prog1, Prog2, UInt1 und SE1 anwenden.
* Komplettes Projekt mit Git, Jenkins und Redmine umgesetzt.
* Teamfähigkeiten verbessern.


## 5. Aufgabenstellung
Im Rahmen eines SE2 Projekts soll ein Spiel JBomberman programmiert werden, welches sehr dem Spielklassiker Bomberman nachempfunden ist, jedoch die Erweiterung bietet über das Netz spielen zu können.
Dabei können bis zu 4 Spieler miteinander spielen (Minimum 2 Spieler).



## 6. Ist-Analyse
Um fordernde und langweilige Vorlesungen zu überbrücken gibt es viele Möglichkeiten,doch es fehlt ganz klar an einem einfachen Spiel das einem über Stunden Freude bereiten kann.
Also sollte hier wenn möglich ein neues Spiel in die Bresche springen sonst verlieren die Studenten noch ganz die Motivation für das Studium.


## 7. Zielsetzung

### 7.1 Programmidee
Bei JBomberman treten 2-4 Spieler gegeneinander an. Es hat derjenige gewonnen, der bis zum Ende überlebt. Ein Bomberman kann Bomben legen, die zeitversetzt detonieren. Das Spielfeld besteht aus zerstörbaren und unzerstörbaren Blöcken. Die zerstörbaren Blöcke können mit einer Bombe gesprengt werden. Beim zerstören eines Blockes erhält man die Möglichkeit auf ein Item, welches die Fähigkeiten eines Bombermans verbessert. Es wird über mehrere Runden gespielt. Falls die Zeit einer Runde abgelaufen ist, wird das Spielfeld verkleinert.  
Das Spiel kann über ein Netzwerk gespielt werden. Ein dedizierter Server übernimmt die Spiellogik und bringt die Clients regelmässig auf den neusten Stand.    
Optional: Zusätzliche Items die einem Bomberman erweiterte Fähigkeiten gewähren


### 7.2 Realisierung
* **Programmiersprache:** Java 8
* **Bibliotheken:** Java2D, Swing
* **Entwicklungsumgebung:** Eclipse Luna
* **Entwicklungswerkzeuge:** Git, Jenkins und Redmine
* **Benutzerschnittstelle:** GUI, Tastatur, Maus
* **Plattform: Desktop**

### 7.3 Anforderungen
Folgende Anforderungen sollen durch JBomberman erfüllt werden:
* Es soll Spass machen
* Netzwerkfähig
* Hohe Testabdeckung

### 7.4 Einschränkungen
JBomberman wird mit Java realisiert, daher wird installiertes Java auf allen Clients vorausgesetzt.
