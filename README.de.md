# LeonScope

[English](README.md) · **Deutsch**

**Full-Stack Developer · AI-Assisted Product Builder**

Ich komme aus der Robotik und kameragestützten Qualitätsprüfung. Bei ZF habe ich Laborprototypen aufgebaut, in denen Roboter, Kameras und Prüfsoftware zusammenarbeiten. Heute beschäftige ich mich mit Webanwendungen und Automatisierung und nutze KI bei der Entwicklung.

## Ausgewählte Projekte

Diese sieben Anwendungen laufen lokal. Auf den Projektseiten findest du Screenshots, die Überlegungen zur Umsetzung und die Testergebnisse.

| Projekt | Was es macht | Zum Weiterlesen |
| :--- | :--- | :--- |
| **[Scope Dispatch](https://github.com/LeonScope/scope-dispatch/blob/main/README.de.md)** | Plant technische Serviceeinsätze nach Qualifikation, Ankunftsfenster und Fahrtzeit. Ein lokales Modell bereitet Anfragen zur Prüfung vor. | [Planungsvergleiche und Prüfungen](https://github.com/LeonScope/scope-dispatch/blob/main/docs/VERIFICATION.md#deutsch) |
| **[Scope Cell](https://github.com/LeonScope/scope-cell/blob/main/README.de.md)** | Simuliert eine UR5e-Prüfzelle mit sichtbaren Bewegungsbefehlen, Bauteilverfolgung und Wiederaufnahme nach Störungen. | [Bewegung, Geometrie und Ablaufprüfungen](https://github.com/LeonScope/scope-cell/blob/main/docs/VERIFICATION.de.md) |
| **[Scope Assist](https://github.com/LeonScope/scope-assist/blob/main/README.de.md)** | Beantwortet Fragen zu ausgewählten technischen Unterlagen mit einem lokalen Sprachmodell und öffnet die zitierte Stelle. | [Modellprüfung und Grenzen](https://github.com/LeonScope/scope-assist/blob/main/docs/VERIFICATION.de.md) |
| **[Scope Vision](https://github.com/LeonScope/visual-quality-inspector/blob/main/README.de.md)** | Erkennt Kratzer und fehlende Bohrungen in erzeugten Bildern von Metallplatten. Anschließend lässt sich eine menschliche Bewertung festhalten. | [Modellauswertung und Tests](https://github.com/LeonScope/visual-quality-inspector/blob/main/docs/VERIFICATION.de.md) |
| **[Scope CRM](https://github.com/LeonScope/crm-portfolio-demo/blob/main/README.de.md)** | Hält Kundenzuständigkeiten, Termine und Notizen zusammen. CSV-Importe werden vor dem Speichern geprüft. | [Rollen, Import und Browsertests](https://github.com/LeonScope/crm-portfolio-demo/blob/main/docs/VERIFICATION.de.md) |
| **[Scope Audit](https://github.com/LeonScope/website-audit-dashboard/blob/main/README.de.md)** | Prüft HTML und interne Links einer Seite, erklärt die Befunde und speichert den Bericht. | [Prüfungen und Grenzen](https://github.com/LeonScope/website-audit-dashboard/blob/main/docs/VERIFICATION.de.md) |
| **[Scope Monitor](https://github.com/LeonScope/service-status-monitor/blob/main/README.de.md)** | Prüft HTTP-Dienste in regelmäßigen Abständen und hält Fehler sowie die anschließende Erholung im Verlauf fest. | [Monitoringregeln und Tests](https://github.com/LeonScope/service-status-monitor/blob/main/docs/VERIFICATION.de.md) |

Die Projekte habe ich mit Codex entwickelt. Die Fallstudien erklären meinen Anteil und den Einsatz der KI. **Öffentlich sind nur die Präsentationen.** Der Quellcode bleibt privat, bei Scope Vision auch Modell sowie Trainings-, Kalibrierungs- und Testdaten. Bei Scope Assist bleiben zusätzlich Modelldateien, Dokumentensammlung und Suchindex privat. Die Laufzeit von Scope Cell und die lokalen Kopien des Robotermodells werden hier ebenfalls nicht veröffentlicht. Bei Scope Dispatch bleiben auch Pläne, Datenbank und Modelldateien privat. Für das eigene Portfolio-Material wird keine Open-Source-Lizenz erteilt. Die Beispiele verwenden erzeugte Daten; die Ergebnisse stammen aus lokalen Tests und nicht aus dem Produktivbetrieb.

### X Model Automation

Für X habe ich mit KI-Unterstützung eine Anwendung aufgebaut, die Medien und Texte vorbereitet, Beiträge für zwei Accounts plant und die Veröffentlichung nachhält. Die [Fallstudie](https://github.com/LeonScope/x-automation-showcase/blob/main/README.de.md) erklärt den Umgang mit unklaren API-Antworten, wiederholten Vorbereitungsfehlern und der Trennung von Testposts und geschäftlichen Auswertungen.

**Stand 19. Oktober 2026:** Die Bildautomation läuft. An der Video-Erweiterung arbeite ich noch. Quellcode, Accountdaten und Betriebsdaten bleiben privat. [Projektstand und berichtete Tests](https://github.com/LeonScope/x-automation-showcase/blob/main/docs/STATUS.de.md).

## Ein weiteres Projekt in Arbeit

Das **Data Integrity Toolkit** prüft, ob Forschungsexporte vollständig und in sich stimmig sind. Fehlende oder widersprüchliche Angaben werden gemeldet, statt Lücken mit angenommenen Werten zu füllen.

Die Tabelle beschreibt die Funktion. Sie zeigt weder die Anwendung selbst noch private Forschungsdaten.

| Eingabe | Ergebnis |
| --- | --- |
| Vollständig und konsistent | Prüfergebnis |
| Verändert oder widersprüchlich | Zurückweisung oder Beschreibung der Unstimmigkeit |
| Unvollständig | Fehlende Angaben werden benannt; Ersatzwerte werden nicht erzeugt |

Das Werkzeug entstand mit KI-Unterstützung. Weitere Integrationsprüfungen sind noch in Vorbereitung. Quellcode, Datensätze, Fachregeln, interne Testunterlagen und Implementierungsdetails bleiben privat.

## Berufliche Erfahrung

### Robotik und Bildverarbeitung bei ZF Friedrichshafen AG

**Softwareentwickler · KTC Saarbrücken · Forschung und Entwicklung · 2021–2024**

Ich habe Fertigungs- und Montageabläufe untersucht, Laborprototypen entwickelt und Roboter, Bildverarbeitungssoftware sowie Bedienoberflächen eingerichtet.

Ein Projekt war ein Prüfprototyp, den ich mit einem Roboter von **Universal Robots** und einer **SensoPart-VISOR-Kamera** eigenständig aufgebaut und konfiguriert habe. Der Roboter entnahm gefräste Mechatronikplatten vom Band, hielt sie in festgelegten Winkeln vor die Kamera und sortierte sie nach dem Prüfergebnis. Benötigte mechanische Teile habe ich technisch gezeichnet und im internen Werkzeugbau fertigen lassen.

Zur Arbeit gehörten das Training bildbasierter Prüfmodelle, die Abstimmung von Grauwerttoleranzen und der Ausgleich wechselnder Lichtverhältnisse im Dreischichtbetrieb. Nach Präsentation und Optimierung führte unsere Abteilung die Lösung schrittweise an **zwölf Fertigungslinien** ein. So wurde die Qualitätsbewertung einheitlicher; Personal- und Ausschusskosten konnten gesenkt werden.

### CRM für einen privaten Auftraggeber

Für einen Auftraggeber habe ich ein webbasiertes CRM mit Kundenverwaltung, Terminen, Benutzerrollen und Datenimport entwickelt, bereitgestellt und in die betrieblichen Abläufe eingebunden.

Das Projekt ist abgeschlossen. Quellcode und Geschäftsdaten des Auftraggebers bleiben vertraulich. Hier beschreibe ich meine damalige Arbeit; der heutige Produktivbetrieb wurde für das Portfolio nicht geprüft.

## Technischer Schwerpunkt

| Bereich | Erfahrung |
| --- | --- |
| Robotik und Bildverarbeitung | Universal Robots · SensoPart VISOR · Kameragestützte Prüfung · Training bildbasierter Prüfmodelle |
| Webentwicklung | PHP · Laravel · JavaScript · TypeScript · React · Node.js · SQL · Git |
| Computer Vision im Portfolio | Python · PyTorch · Vortrainierte Bildmerkmale · Anomalieerkennung · Getrennte Modellauswertung |
| Lokale Dokumenten-KI | Dokumentensuche · Lokale Sprachmodelle · Quellenbelege · Wiederholbare Prüfungen |
| Einsatzplanung im Portfolio | Planung mit Nebenbedingungen · Routenplanung · Lokale KI-Erfassung · Geprüfte Planänderungen |
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
