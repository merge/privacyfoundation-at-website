---
title: "Was ist Tor?"
date: 2018-04-06T17:16:06+02:00
---

`Jede Person hat das Recht auf freie Meinungsäußerung. Dieses Recht schließt die Meinungsfreiheit und die Freiheit ein, Informationen und Ideen ohne behördliche Eingriffe und ohne Rücksicht auf Staatsgrenzen zu empfangen und weiterzugeben.` [Charta der Grundrechte der EU, Art.11 (1)]

`Jedermann hat, insbesondere auch im Hinblick auf die Achtung seines Privat- und Familienlebens, Anspruch auf Geheimhaltung der ihn betreffenden personenbezogenen Daten, soweit ein schutzwürdiges Interesse daran besteht. (...)` [Österreichisches Datenschutzgesetz §1.(1)]

Beim Nutzen des Internets ist es nicht klar, wer die Möglichkeit zur gesamten oder teilweisen Spionage der Kommunikation hat. Tor kann dieses Ungleichgewicht zu Gunsten der Integrität und Sicherheit von Menschen und Unternehmen verkleinern.

[Informationsfreiheit](http://de.wikipedia.org/wiki/Informationsfreiheit) und [Meinungsfreiheit](http://de.wikipedia.org/wiki/Meinungsfreiheit) für Nutzer setzt die Möglichkeit zu Anonymität vorraus. Anonymität bietet Nutzern auch die Möglichkeit, Kontrolle über entstehende Daten zu haben. Tor versucht, für jeden Menschen nutzbar zu sein und für viele ist Tor dazu auch die einzige Möglicheit.

## Internetnutzung über Tor

[Tor Browser](https://www.torproject.org/download/download.html) kann einfach heruntergeladen, entpackt und gestartet werden. Er ist nicht zu 'installieren' und einfach als 'Zweitbrowser' verwendbar.

Folgende Grafiken zeigen im Vergleich, welche Informationen wem zugänglich sind, wenn einerseits https in einem herkömmlichen Browser und andererseits https im Tor Browser genutzt wird. Wer den 'Ort' der Nutzer kennt, kann sie meist identifizieren. Im Tor Browser 'zeigst' du Beobachtern, dass du Tor nutzt - nicht was du online liest.

Sichtbare Informationen bei normalen Browsern (Internetverbindungen) mit https. Kritisch ist die Kombination 'Site.com' usw. gemeinsam mit 'Ort':

![https direkt im Internet](https://people.torproject.org/~lunar/tor-and-https/de/tor-and-https-1.png)

Sichtbare Informationen mit Tor Browser. Keine Kombination 'Site.com' usw. mit 'Ort':

![https im Tor Browser](https://people.torproject.org/~lunar/tor-and-https/de/tor-and-https-3.png)

[Quelle](https://people.torproject.org/~lunar/tor-and-https/), [Lizenz](https://people.torproject.org/~lunar/tor-and-https/LICENSE)

## Onion Services

Die Tor Software wird auch dazu genutzt, Inhalte sicher anzubieten. Um als Anbieter seine Inhalte unzensiert und zuverlässig angeboten zu wissen, wird also Tor als Webserver genutzt und eine [.onion](https://de.wikipedia.org/wiki/.onion) Adresse erstellt. Einige Beispiele sind die [New York Times](https://www.nytimes3xbfgragh.onion/), [DuckDuckGo](https://3g2upl4pq6kufc4m.onion/) oder [Facebook](https://www.facebookcorewwwi.onion/).

Onion Services werden oft als 'Dark Web' oder ähnlich bezeichnet. Es gibt natürlich nur ein Internet, aber Onion Services können auch dazu genutzt werden, den Ort des Anbieters zu verstecken, was leider auch missbraucht wird. Allgemein können illegale Inhalte im Internet immer bei [Stopline.at](https://www.stopline.at/) gemeldet werden.

## Das Tor Projekt

Das [Tor Projekt](https://torproject.org) erforscht, entwirft, implementiert und analysiert anonyme Kommunikationssysteme. Im Fokus liegen praktische Systeme für 'low-latency' (interaktive) Internetverbindungen (z.B. Webseiten, Chat, ...), die Spionage, Datenanalyse und andere Angriffen von außen oder innen (Tor Server) standhält. Tor verhindert, dass darunterliegende Ebenen (Internet Infrastruktur) wissen, wer mit wem kommuniziert -- das Internet weiß (nur), dass Kommunikation stattfindet. Zusätzlich werden Inhalte der Kommunikation versteckt (verschlüsselt), bis sie das Tor-Netz verlassen.

## Disclaimer

Austrian Privacy Foundation is not affiliated with the Tor project. "Tor" and the "Onion Logo" are registered trademarks of The Tor Project, Inc.
