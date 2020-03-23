---
layout: post
title: "Integration-Testing mit Docker und Testcontainers (Kevin Wittek)"
date: 20-04-2020 20:15
description: "Treffen am 20.04.2020 um 20:15 Uhr"
keywords: "testcontainers"
---

<b>{{ page.description }}</b>

### Beschreibung

Integration-Tests sind für viele ein notwendiges Übel.
Manuelle Installation und Konfiguration der lokalen Testumgebung oder eine Testinfrastruktur, die sich mehrere Entwickler und Teams teilen müssen sorgen dafür, dass viele Entwickler versuchen auf aufwändige Integration-Tests zu verzichten.
Dabei können uns Integration-Tests allerdings ein Vertrauen in unseren Code und die Integration mit externen System liefern, der weit über die Möglichkeiten von Unit-Tests hinausgeht.

Container-Technologien wie Docker ermöglichen es uns, unser bisheriges Verhältnis zu Integration-Tests, als Teil des Entwicklungsprozesses, grundlegend zu hinterfragen.
Dank Docker haben wir die Möglichkeit unsere komplette Test-Suite bestehend aus Unit-, Integration- und Acceptance-Tests, direkt aus unserem Code-Repository starten. Die dafür benötigte Infrastruktur beschreiben direkt als Code.

Zu diesem Zweck werden wir uns die [Testcontainers](https://github.com/testcontainers/testcontainers-java) Java-Library anschauen.
Diese ermöglicht es uns, die für unsere Tests benötigten Container direkt als Teil unserer JUnit-Tests zu beschreiben.
Mithilfe von Testcontainers werden wir lernen, wie wir Integration-Tests für verschiedene Persistenztechnologien (RDBMS, NoSQL) schreiben, Datenbankmigrationen testen und die Integration mit externen REST-Services sicherstellen.
Darüber hinaus werden wir allerdings noch einen Schritt weitergehen und komplette Acceptance-Tests für unsere Microservice-Architektur schreiben, in dem wir den speziellen Testcontainers-Support zusammen mit den Werkzeugen Docker-Compose und Selenium verwenden.

Und obwohl Testcontainers eine Java-Library ist werden wir auch sehen, wie wir Anwendungen in anderen Sprachen mithilfe von Testcontainers Blackbox-Testen können.

### Über den Speaker

**Kevin Wittek** <a href="https://twitter.com/kiview"><i class="fa fa-twitter"></i></a>

*Kevin ist Testcontainers Co-Maintainer und Testcontainers-Spock-Autor sowie verliebt in FLOSS.
Er erhielt den Oracle Groundbreaker Ambassador Award für seine Beiträge zur Open-Source-Community.
Er ist Software-Crafter und Test-Fan.
Er spielt die elektrische Gitarre und ist Musiker in seinem zweiten Leben.
Er gründete während seiner Universitätszeit seine eigene Firma und entwickelte mobile Anwendungen und Client-Server-Applikationen, die ihn mit Grails und dem Groovy-Ökosystem bekannt machten.
Hier verliebte er sich wegen Spock in TDD.
Nachdem er viele Jahre als Ingenieur in der Industrie gearbeitet hat, promoviert Kevin jetzt am Institut für Internetsicherheit und leitet ein Forschungsteam im Bereich "Blockchain-Technologie".*

### Anmeldung

Wir verwenden die Online-Webinarlösung [zoom](https://www.zoom.us/), die uns freundlicher Weise von [INNOQ](https://innoq.com/) gesponsort wird. Hier geht es zur Registrierung:

<https://zoom.us/webinar/register/WN_M2cNymA8QUe_O2W4ggPU4Q>

Kleiner Tipp: Statt der Installation des Zoom-Clients ist auch der direkte Zugang über den Browser möglich ([Hinweisbild](/assets/images/zoom_direct_access.jpg))

Evtl. kurzfristige Änderungsmitteilungen gibt es über [Twitter](https://twitter.com/cyberjug). Aktuelles zur Organisation der CyberJUG findet sich im [jvm-german Slack-Channel](https://slackin-jvm-german.herokuapp.com/) #cyberjug .
