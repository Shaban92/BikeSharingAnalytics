# BikeSharingAnalytics

## Ziele

### Ziel 1: Tägliche Nutzungsprognose
Entwicklung eines Modells, das die Anzahl der täglichen Fahrradvermietungen basierend auf verschiedenen Faktoren (z.B. Wetterbedingungen, Wochentag etc.) vorhersagt. Dies kann dem Unternehmen helfen, seine Ressourcen effektiver zu verwalten und die Kundenzufriedenheit zu erhöhen.

### Ziel 2: Tägliche Nutzungsanalyse
Erstellung detaillierter Berichte zur täglichen Nutzung des Bike-Sharing-Dienstes, einschließlich (aber nicht beschränkt auf):

- Gesamtzahl der Nutzer über verschiedene Zeiträume
- Die Stoßzeiten des Dienstes
- Beziehung zwischen Wetterbedingungen und Nutzung
- Andere relevante Nutzungsmuster oder Trends

## Plan

- **Datenbeschaffung und -bereinigung**: Laden Sie den öffentlichen Fahrradverleih-Datensatz von der UCI Machine Learning Repository herunter. Überprüfen und bereinigen Sie die täglichen Daten, um sicherzustellen, dass sie für die Analyse geeignet sind.

- **Explorative Datenanalyse (EDA)**: Untersuchen Sie die täglichen Daten, um ein Verständnis für ihre Struktur und die Beziehungen zwischen verschiedenen Merkmalen zu gewinnen.

- **Modellbildung**: Verwenden Sie geeignete Machine-Learning-Techniken, um ein Modell zur Vorhersage der täglichen Fahrradverleihzahl zu entwickeln.

- **Evaluation und Optimierung des Modells**: Überprüfen Sie die Leistung Ihres Modells und optimieren Sie es, um die Genauigkeit der Vorhersagen zu verbessern.

- **Berichterstellung**: Erstellen Sie detaillierte Berichte, die die Ergebnisse Ihrer Analysen und Vorhersagen präsentieren. Stellen Sie sicher, dass die Berichte für Nicht-Techniker verständlich sind.

- **Präsentation der Ergebnisse**: Präsentieren Sie Ihre Ergebnisse in einer Weise, die das Verständnis und die Entscheidungsfindung des Unternehmens erleichtert.

## Zukünftige Pläne
Erweiterung der Analyse und Modellierung auf stündliche Daten, um noch detailliertere Einblicke und Prognosen zu ermöglichen.

## Projektstruktur

BikeSharingAnalytics/ (Hauptordner für Ihr Projekt)
│
├──📜 README.md (Markdown, die Hauptdokumentation und das Einführungsmaterial für Ihr Projekt)
│
├──📝 .gitignore (Datei, um bestimmte Dateien von der Versionskontrolle auszuschließen)
│
├──📋 environment.yml (conda-Umgebungsdatei)
│
├──📁 data/ (alle Daten, die für das Projekt verwendet werden)
│   ├──📂 raw_data/ (die Rohdaten, die direkt aus der UCI Machine Learning Repository stammen)
│   │   ├──📄 hour.csv (stündliche Daten - für zukünftige Arbeit)
│   │   └──📄 day.csv (tägliche Daten - akt## BikeSharingAnalytics


