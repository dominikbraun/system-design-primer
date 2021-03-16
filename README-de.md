*[English](README.md) ∙ [日本語](README-ja.md) ∙ [简体中文](README-zh-Hans.md) ∙ [繁體中文](README-zh-TW.md) | [العَرَبِيَّة‎](https://github.com/donnemartin/system-design-primer/issues/170) ∙ [বাংলা](https://github.com/donnemartin/system-design-primer/issues/220) ∙ [Português do Brasil](https://github.com/donnemartin/system-design-primer/issues/40) ∙ [Deutsch](README-de.md) ∙ [ελληνικά](https://github.com/donnemartin/system-design-primer/issues/130) ∙ [עברית](https://github.com/donnemartin/system-design-primer/issues/272) ∙ [Italiano](https://github.com/donnemartin/system-design-primer/issues/104) ∙ [한국어](https://github.com/donnemartin/system-design-primer/issues/102) ∙ [فارسی](https://github.com/donnemartin/system-design-primer/issues/110) ∙ [Polski](https://github.com/donnemartin/system-design-primer/issues/68) ∙ [русский язык](https://github.com/donnemartin/system-design-primer/issues/87) ∙ [Español](https://github.com/donnemartin/system-design-primer/issues/136) ∙ [ภาษาไทย](https://github.com/donnemartin/system-design-primer/issues/187) ∙ [Türkçe](https://github.com/donnemartin/system-design-primer/issues/39) ∙ [tiếng Việt](https://github.com/donnemartin/system-design-primer/issues/127) ∙ [Français](https://github.com/donnemartin/system-design-primer/issues/250) | [Add Translation](https://github.com/donnemartin/system-design-primer/issues/28)*

**Helfe diesen Leitfaden zu [übersetzen](TRANSLATIONS.md)!**

# The System Design Primer

<p align="center">
  <img src="images/jj3A5N8.png">
  <br/>
</p>



## Motivation

> Lernt zum großflächig Systeme entwurfen.
>
> Vorbereitet sich für das System-Design Interview.

### Lernt zum großflächig Systeme entwurfen

Lernen zum scalierbares Systeme entwurfen werden dir helfen um ein besserer Ingenieur zu werden.

System-Design ist ein breites Fach. Es gibt **viel Ressourcen streuert  im ganzen Internet** über System-Design Prizipien.

Dieses Repo ist ein **organizierte Sammlung** der Ressourcen um dir zu helfen wie man Systeme im Maßstab erbaut lernen.

### Lernt von der Open-Source Gemeinschaft

Dies ist ein ständig aktualisiert, Open-Source Projekt.

[Mitwirkungen](#mitwirken) sind wilkommen!

### Vorbereitet sich für das System-Design Interview

In Ergänzung zu Coding Interviews, System-Design ist ein **erforderliche Komponente** dem **technisches Interview Verfahren** an viele Computerfirmen.

**Übt häufige System-Design Interview Fragen** und **vergleichen** deine Ergebnisse mit **Probenlösungen**: Diskussionen, Code, und Diagramme.

Zusätzliche Themen für die Vorbereitung auf ein Coding Interview:

* [Study guide](#study-guide)
* [Wie man ein Interview Frage System-Design enträtselt](#how-to-approach-a-system-design-interview-question)
* [Interview Fragen System-Design, **mit Lösungen**](#system-design-interview-questions-with-solutions)
* [Interview Fragen Objektorientiertes Design, **mit Lösungen**](#object-oriented-design-interview-questions-with-solutions)
* [Zusätzliche Interview Fragen System-Design](#additional-system-design-interview-questions)



## Anki Karteikarten

<p align="center">
  <img src="images/zdCAkB3.png">
  <br/>
</p>

Die hier zur Verfügung gestellten [Anki Karteikarten](https://apps.ankiweb.net/) nutzen das Konzept der verteilten Wiederholung. Damit sollst du beim Behalten der Schlüsselkonzepte des System Designs unterstützt werden.

* [Karteikarten System Design](https://github.com/donnemartin/system-design-primer/tree/master/resources/flash_cards/System%20Design.apkg)
* [Übungskarteikarten System Design](https://github.com/donnemartin/system-design-primer/tree/master/resources/flash_cards/System%20Design%20Exercises.apkg)
* [Übungskarteikarten Objektorientiertes Design](https://github.com/donnemartin/system-design-primer/tree/master/resources/flash_cards/OO%20Design.apkg)

Super um unterwegs zu üben!

### Coding Ressourcen: Interaktive Coding Herausforderungen

Auf der Suche nach Ressourcen um dich bei der Vorbereitung auf ein [**Coding Interview**](https://github.com/donnemartin/interactive-coding-challenges) vorzubereiten?

<p align="center">
  <img src="images/b4YtAEN.png">
  <br/>
</p>

Schau dir das Partner Repo [**Interactive Coding Herausforderungen**](https://github.com/donnemartin/interactive-coding-challenges) mit einem zusätzlichen Anki Deck an:

* [Coding Deck](https://github.com/donnemartin/interactive-coding-challenges/tree/master/anki_cards/Coding.apkg)



## Mitwirken

> Lernt von der Gemeinschaft.

Zögere nicht durch Pull Requests zu helfen:

* Fehler beheben
* Abschnitte verbessern
* Abschnitte hinzufügen
* [Übersetzen](https://github.com/donnemartin/system-design-primer/issues/28)

Inhalte die etwas verbessert werden können finden sich [in Entwicklung](#in-entwicklung).

Beachte die [Richtlinien zum Mitwirken](CONTRIBUTING.md).


## Study guide

> Suggested topics to review based on your interview timeline (short, medium, long).

![Imgur](images/OfVllex.png)

**Q: For interviews, do I need to know everything here?**

**A: No, you don't need to know everything here to prepare for the interview**.

What you are asked in an interview depends on variables such as:

* How much experience you have
* What your technical background is
* What positions you are interviewing for
* Which companies you are interviewing with
* Luck

More experienced candidates are generally expected to know more about system design.  Architects or team leads might be expected to know more than individual contributors.  Top tech companies are likely to have one or more design interview rounds.

Start broad and go deeper in a few areas.  It helps to know a little about various key system design topics.  Adjust the following guide based on your timeline, experience, what positions you are interviewing for, and which companies you are interviewing with.

* **Short timeline** - Aim for **breadth** with system design topics.  Practice by solving **some** interview questions.
* **Medium timeline** - Aim for **breadth** and **some depth** with system design topics.  Practice by solving **many** interview questions.
* **Long timeline** - Aim for **breadth** and **more depth** with system design topics.  Practice by solving **most** interview questions.

| | Short | Medium | Long |
|---|---|---|---|
| Read through the [System design topics](#index-of-system-design-topics) to get a broad understanding of how systems work | :+1: | :+1: | :+1: |
| Read through a few articles in the [Company engineering blogs](#company-engineering-blogs) for the companies you are interviewing with | :+1: | :+1: | :+1: |
| Read through a few [Real world architectures](#real-world-architectures) | :+1: | :+1: | :+1: |
| Review [How to approach a system design interview question](#how-to-approach-a-system-design-interview-question) | :+1: | :+1: | :+1: |
| Work through [System design interview questions with solutions](#system-design-interview-questions-with-solutions) | Some | Many | Most |
| Work through [Object-oriented design interview questions with solutions](#object-oriented-design-interview-questions-with-solutions) | Some | Many | Most |
| Review [Additional system design interview questions](#additional-system-design-interview-questions) | Some | Many | Most |



## In Entwicklung

Interessiert ein Abschnitt Hinzufügen oder einen in Bearbeitung zu ergänzen?  [Mitwirken](#mitwirken)!

* Verteiltes Rechnen mit MapReduce (Distributed computing with MapReduce)
* Konsistentes Hashing (Consistent hashing)
* Streuung sammeln (Scatter gather)
* [Mitwirken](#mitwirken)
