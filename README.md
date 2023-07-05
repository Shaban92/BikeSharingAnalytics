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

- 📁 BikeSharingAnalytics
  - 📜 README.md: "Hauptdokumentation und Einführungsmaterial für das Projekt"
  - 📝 .gitignore: # Datei, um bestimmte Dateien von der Versionskontrolle auszuschließen
  - 📋 environment.yml:  // conda-Umgebungsdatei
  - 📁 data: \\ Alle Daten, die für das Projekt verwendet werden
    - 📁 raw_data: Die Rohdaten, die direkt aus der UCI Machine Learning Repository stammen
      - 📄 hour.csv: Stündliche Daten - für zukünftige Arbeit
      - 📄 day.csv: Tägliche Daten - aktueller Fokus
    - 📁 processed_data: Die aufbereiteten Daten, die für die Analyse und Modellierung bereit sind
  - 📓 notebooks: Jupyter-Notebooks für explorative Datenanalyse, Modellentwicklung und andere Aufgaben
    - 📖 data_exploration.ipynb: Explorative Datenanalyse
    - 📖 data_preprocessing.ipynb: Datenbereinigung und -vorbereitung
    - 📖 model_development.ipynb: Entwicklung der Vorhersagemodelle
    - 📖 model_evaluation.ipynb: Evaluierung der Modellleistung und Berichterstellung
  - 📁 scripts: Alle Skripte, die für das Projekt verwendet werden
    - 📜 data_preparation.py: Skript zur Datenvorbereitung und -reinigung
    - 📜 model.py: Skript zur Erstellung der Vorhersagemodelle
    - 📜 utils.py: Hilfsfunktionen und -skripte, die in verschiedenen Teilen des Projekts verwendet werden
  - 📁 reports: Ordner für die erstellten Berichte zur Fahrradnutzung
    - 📜 usage_report.pdf: Bericht zur allgemeinen Nutzung
    - 📜 weather_impact_report.pdf: Bericht zum Einfluss des Wetters auf die Nutzung
    - 📜 peak_times_report.pdf: Bericht zu Stoßzeiten
  - 📁 output: Die Ergebnisse der Modellvorhersagen und Leistungsmetriken
    - 📂 predictions: Die Vorhersagen der verschiedenen Modelle
    - 📂 performance_metrics: Enthält die Leistungsmetriken der Modelle
  - 📁 future_expansions: Materialien und Pläne für zukünftige Erweiterungen, wie die Einbeziehung stündlicher Daten
