# LeonScope

[English](README.md) · **Deutsch**

**Full-Stack Developer · AI-Assisted Product Builder**

Ich entwickle Software und Automatisierung für praktische Geschäfts- und Fertigungsabläufe. Meine Erfahrung verbindet industrielle Robotik, kameragestützte Qualitätsprüfung und Webanwendungen mit KI-gestützter Produktentwicklung.

Ich arbeite von klaren Anforderungen über Prototypen und Umsetzung bis zu Tests und Dokumentation. Meine Lösungen sollen verständlich, nützlich und überprüfbar sein.

## Referenzprojekte

**[CRM Portfolio Demo](https://github.com/LeonScope/crm-portfolio-demo/blob/main/README.de.md)** — ein eigenständiges Laravel-CRM mit Kundenzuständigkeiten, Terminen, Änderungsverlauf und CSV-Import mit Vorschau und Bestätigung. Mit KI-Unterstützung und erfundenen Daten entwickelt.

Die öffentliche Präsentation enthält Screenshots, eine Fallstudie und dokumentierte lokale Ergebnisse: **53 Anwendungstests, 430 Einzelprüfungen und 4 Browserabläufe bestanden**. Der Anwendungscode bleibt privat; eine Open-Source-Lizenz wird nicht erteilt.

[Fallstudie](https://github.com/LeonScope/crm-portfolio-demo/blob/main/docs/CASE-STUDY.de.md) · [Prüfergebnisse](https://github.com/LeonScope/crm-portfolio-demo/blob/main/docs/VERIFICATION.de.md)


**[Scope Audit · Website Audit Dashboard](https://github.com/LeonScope/website-audit-dashboard/blob/main/README.de.md)** — eine Anwendung mit TypeScript und React für begrenzte Website-Prüfungen, interne Links, lokalen Berichtsverlauf und JSON-/CSV-Exporte. Bestätigte Fehlerstatus und unbestimmte Ergebnisse bleiben unterscheidbar.

**64 automatisierte Anwendungstests und fünf Browserabläufe in einer frischen lokalen Kopie bestanden.** Die Präsentation enthält Desktop-/Smartphone-Ansichten und einen gesonderten echten HTTP-Abruf. Der Anwendungscode bleibt privat.

[Fallstudie](https://github.com/LeonScope/website-audit-dashboard/blob/main/docs/CASE-STUDY.de.md) · [Prüfergebnisse](https://github.com/LeonScope/website-audit-dashboard/blob/main/docs/VERIFICATION.de.md)

**[Scope Monitor · Service Status Monitor](https://github.com/LeonScope/service-status-monitor/blob/main/README.de.md)** — regelmäßige HTTP-Prüfungen, Antwortzeitverlauf und Störungen, die durch aufeinanderfolgende Messungen bestätigt werden. Mit Pause/Fortsetzung, JSON-/CSV-Exporten und lokalem Ereignisprotokoll.

**72 automatisierte Anwendungstests und acht Browserabläufe in einer frischen lokalen Kopie bestanden.** Die Präsentation trennt simulierte Beispiele von einem gesonderten echten HTTP-Abruf. Die Überwachung läuft lokal; der Anwendungscode bleibt privat.

[Fallstudie](https://github.com/LeonScope/service-status-monitor/blob/main/docs/CASE-STUDY.de.md) · [Prüfergebnisse](https://github.com/LeonScope/service-status-monitor/blob/main/docs/VERIFICATION.de.md)

**[Scope Vision · Visual Quality Inspector](https://github.com/LeonScope/visual-quality-inspector/blob/main/README.de.md)** — lokale Bildprüfung mit berechneten Abweichungsmarkierungen, getrennten menschlichen Bewertungen und nachvollziehbarem Prüfverlauf. Verbindet ein vortrainiertes Bildnetz mit lokal gelernten normalen Bildmerkmalen.

**46 automatisierte Anwendungs-/Modellprüfungen und acht Browserabläufe in einer frischen lokalen Kopie bestanden.** Auf 180 getrennten synthetischen Testbildern: 120 von 120 Fehlern erkannt, kein Fehlalarm bei 60 fehlerfreien Bildern. Diese Messung gilt für die begrenzte synthetische Aufgabe; eine industrielle Zuverlässigkeit wird nicht behauptet. Quellcode, Trainingsdaten und Modell bleiben privat.

[Fallstudie](https://github.com/LeonScope/visual-quality-inspector/blob/main/docs/CASE-STUDY.de.md) · [Prüfergebnisse](https://github.com/LeonScope/visual-quality-inspector/blob/main/docs/VERIFICATION.de.md)

**Data Integrity Toolkit** — ein privates, offline ausgerichtetes Werkzeug zur Prüfung von Vollständigkeit und Konsistenz von Forschungsexporten. Fehlende oder ungeprüfte Angaben bleiben von bestätigten Ergebnissen unterscheidbar.

Die vereinfachte Übersicht zeigt die Funktion; sie ist weder eine Live-Ansicht der Anwendung noch eine Offenlegung der zugrunde liegenden Eingaben.

| Situation | Sichtbares Ergebnis |
| --- | --- |
| Vollständige, konsistente Eingabe | Ein klares Prüfergebnis |
| Veränderte oder widersprüchliche Eingabe | Zurückweisung oder ein ausdrücklicher Hinweis auf die Unstimmigkeit |
| Unvollständige Eingabe | Fehlende Angaben bleiben sichtbar; Werte werden nicht erfunden |

Mit KI-Unterstützung entwickelt, mit Schwerpunkt auf Datenvalidierung und sorgfältigen Tests. Weitere Integrationsprüfungen sind in Vorbereitung. Quellcode, Datensätze, Fachregeln, interne Testunterlagen und Implementierungsdetails bleiben privat.

## Ausgewählte Erfahrung

### Robotik, KI und Bildverarbeitung — ZF Friedrichshafen AG

**Softwareentwickler · KTC Saarbrücken · Forschung und Entwicklung · 2021–2024**

- Analyse von Fertigungs- und Montageprozessen, Entwicklung eigener Laborprototypen sowie Konfiguration von Robotern, Bildverarbeitungssoftware und grafischen Bedienoberflächen.
- Eigenständiger Aufbau und vollständige Konfiguration eines Prüfprototyps mit einem Roboter von **Universal Robots** und einem **SensoPart-VISOR-Kamerasystem**. Der Roboter präsentierte gefräste Mechatronikplatten in definierten Posen und Winkeln vor der Kamera und sortierte sie anschließend nach Prüfergebnis in i. O. / n. i. O.
- Training bildbasierter Prüfmodelle, Abstimmung von Grauwerttoleranzen und Kompensation von Lichtschwankungen für den Dreischichtbetrieb. Technische Zeichnungen für mechanische Komponenten, die im internen Werkzeugbau gefertigt wurden.
- Nach Präsentation und Optimierung integrierte die Abteilung die Lösung schrittweise an **zwölf Fertigungslinien**. Das vereinheitlichte die Qualitätsbewertung und trug zur Senkung von Personal- und Ausschusskosten bei.

### Geschäftsanwendungen — CRM für einen privaten Auftraggeber

Konzeption, Entwicklung und Bereitstellung einer webbasierten CRM-Anwendung mit Kundenverwaltung, Terminen, rollenbasierten Abläufen, Datenimport und Einbindung in die betrieblichen Prozesse.

Das Kundenprojekt ist abgeschlossen. Quellcode und Geschäftsdaten bleiben vertraulich; der aktuelle Produktivbetrieb ist nicht Gegenstand dieses Portfolios.

## Technischer Schwerpunkt

| Bereich | Erfahrung |
| --- | --- |
| Robotik und Bildverarbeitung | Universal Robots · SensoPart VISOR · Kameragestützte Prüfung · Training bildbasierter Prüfmodelle |
| Webentwicklung | PHP · Laravel · JavaScript · TypeScript · React · Node.js · SQL · Git |
| Computer Vision im Portfolio | Python · PyTorch · Vortrainierte Bildmerkmale · Anomalieerkennung · Getrennte Modellauswertung |
| Entwicklungspraxis | Prozessanalyse · Prototypenentwicklung · Workflow-Automatisierung · APIs · Datenvalidierung |

## KI-Weiterbildung

**Google / Coursera — acht abgeschlossene KI-Kurse**, Oktober 2026.

<details>
<summary>Alle acht Google-Kurse anzeigen</summary>

- AI Fundamentals
- AI for Brainstorming and Planning
- AI for Writing and Communicating
- AI for Research and Insights
- AI for Content Creation
- AI for Data Analysis
- AI for App Building
- AI for App Deployment

</details>

**AWS Training & Certification — Foundations of Prompt Engineering**, abgeschlossen im Oktober 2026.

[Meine öffentlichen Repositories ansehen](https://github.com/LeonScope?tab=repositories)
