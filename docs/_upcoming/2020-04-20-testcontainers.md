---
layout: post
title: "Integration-Testing mit Docker und Testcontainers (Kevin Wittek)"
date: 20-04-2020 20:15
description: "Treffen am 20.04.2020 um 20:15 Uhr"
keywords: "testcontainers"
published: false
---

<b>{{ page.description }}</b>

<br/>

Unit-Tests sind in Ordnung, aber ohne ordnungsgemäße Integrationstests, insbesondere wenn sie mit externen Ressourcen wie Datenbanken und anderen Diensten arbeiten, wissen wir möglicherweise nicht, wie sich die Anwendung nach der Deployment in der realen Produktionsumgebung tatsächlich verhalten wird.
Vor Docker war die Konfiguration der Umgebung für Integrationstests schmerzhaft - die Leute verwendeten Fake-Datenbankimplementierungen und mockten Server. In der Regel war es nicht auch plattformübergreifend.
Dank Docker können wir die Umgebung jetzt jedoch schnell für unsere Tests vorbereiten.

In diesem Vortrag möchte ich zeigen, wie auch Du [Testcontainer](https://github.com/testcontainers/testcontainers-java) verwenden kannst.
Testcontainer ist eine beliebte Java-Testbibliothek, die Docker nutzt, um Testabhängigkeiten einfach und zuverlässig zu bereitzustellen. 
Wir werden Testcontainer mit einem Spring Boot Microservice verwenden und gegen echte PostgreSQL- und MongoDB-Data-Stores testen.
Wir werden unseren Service von anderen Microservices isolieren, dann Selenium-Browser in Docker starten und unsere Anwendung testen &ndash; und das alles mit derselben Bibliothek! 

<br/>

*Über Kevin Wittek*

*Kevin ist Testcontainers Co-Maintainer und Testcontainers-Spock-Autor sowie verliebt in FLOSS.
Er erhielt den Oracle Groundbreaker Ambassador Award für seine Beiträge zur Open-Source-Community.
Er ist Software-Crafter und Test-Fan.
Er spielt die elektrische Gitarre und ist Musiker in seinem zweiten Leben.
Er gründete während seiner Universitätszeit seine eigene Firma und entwickelte mobile Anwendungen und Client-Server-Applikationen, die ihn mit Grails und dem Groovy-Ökosystem bekannt machten.
Hier verliebte er sich wegen Spock in TDD.
Nachdem er viele Jahre als Ingenieur in der Industrie gearbeitet hat, promoviert Kevin jetzt am Institut für Internetsicherheit und leitet ein Forschungsteam im Bereich "Blockchain-Technologie".*

<br>

**Anmeldung**

Wir verwenden die Online-Konferenzlösung [BigMarker](https://www.bigmarker.com/), die uns freundlicher Weise von [Neo4j](https://neo4j.com/) zur Verfügung gestellt wird.

*Die Anmeldung wird hier ca. zwei Wochen vor dem Event freigeschalten.*

Neuigkeiten gibt es über [Twitter](https://twitter.com/cyberjug). Aktuelles zur Organisation der CyberJUG findet sich im [jvm-german Slack-Channel](https://slackin-jvm-german.herokuapp.com/) #cyberjug .
