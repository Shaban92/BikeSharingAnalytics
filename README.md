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

## Datenquelle

Die Daten für dieses Projekt stammen aus der [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php), die sowohl stündliche als auch tägliche Fahrradverleihdaten aus Washington D.C., USA enthält.

## Installationsanleitung

1. Stellen Sie sicher, dass Python und pip auf Ihrem System installiert sind. 
2. Klonen Sie dieses Repository auf Ihre Maschine und navigieren Sie in das Projektverzeichnis:
    ```bash
    git clone https://github.com/your-username/BikeSharingAnalytics.git
    cd BikeSharingAnalytics
    ```
3. Erstellen Sie eine neue Python-Virtualenv-Umgebung und aktivieren Sie sie:
    ```bash
    python3 -m venv env
    source env/bin/activate  # Für Linux und Mac
    .\env\Scripts\activate  # Für Windows
    ```
4. Installieren Sie die erforderlichen Pakete mit pip:
    ```bash
    pip install -r requirements.txt
    ```

## Anleitung zur Ausführung des Projekts

Nachdem Sie die Umgebung aktiviert und die notwendigen Pakete installiert haben, können Sie die Jupyter Notebooks starten:

```bash
jupyter notebook
```
Navigieren Sie zum Verzeichnis notebooks und öffnen Sie die Notebooks, um die Analyse und Modellentwicklung zu starten.

## Ergebnisse und Berichte

Alle Ergebnisse der Analyse sowie die entwickelten Modelle werden in den entsprechenden Jupyter-Notebooks präsentiert. Zusätzlich finden Sie detaillierte Berichte zu Aspekten wie Fahrradnutzung, Wettereinfluss und Stoßzeiten im reports-Verzeichnis.

## Projektstruktur

- 📁 BikeSharingAnalytics
  - 📜 README.md: // Hauptdokumentation und Einführungsmaterial für das Projekt
  - 📝 .gitignore: // Datei, um bestimmte Dateien von der Versionskontrolle auszuschließen
  - 📋 environment.yml:  // conda-Umgebungsdatei
  - 📁 data: // Alle Daten, die für das Projekt verwendet werden
    - 📁 raw_data: // Die Rohdaten, die direkt aus der UCI Machine Learning Repository stammen
      - 📄 hour.csv: // Stündliche Daten - für zukünftige Arbeit
      - 📄 day.csv: // Tägliche Daten - aktueller Fokus
    - 📁 processed_data: // Die aufbereiteten Daten, die für die Analyse und Modellierung bereit sind
  - 📓 notebooks: // Jupyter-Notebooks für explorative Datenanalyse, Modellentwicklung und andere Aufgaben
    - 📖 data_exploration.ipynb: // Explorative Datenanalyse
    - 📖 data_preprocessing.ipynb: // Datenbereinigung und -vorbereitung
    - 📖 model_development.ipynb: // Entwicklung der Vorhersagemodelle
    - 📖 model_evaluation.ipynb: // Evaluierung der Modellleistung und Berichterstellung
  - 📁 scripts: // Alle Skripte, die für das Projekt verwendet werden
    - 📜 data_preparation.py: // Skript zur Datenvorbereitung und -reinigung
    - 📜 model.py: // Skript zur Erstellung der Vorhersagemodelle
    - 📜 utils.py: // Hilfsfunktionen und -skripte, die in verschiedenen Teilen des Projekts verwendet werden
  - 📁 reports: // Ordner für die erstellten Berichte zur Fahrradnutzung
    - 📜 usage_report.pdf: // Bericht zur allgemeinen Nutzung
    - 📜 weather_impact_report.pdf: // Bericht zum Einfluss des Wetters auf die Nutzung
    - 📜 peak_times_report.pdf: // Bericht zu Stoßzeiten
  - 📁 output: // Die Ergebnisse der Modellvorhersagen und Leistungsmetriken
    - 📂 predictions: // Die Vorhersagen der verschiedenen Modelle
    - 📂 performance_metrics: // Enthält die Leistungsmetriken der Modelle
  - 📁 future_expansions: // Materialien und Pläne für zukünftige Erweiterungen, wie die Einbeziehung stündlicher Daten

## Forschungsfragen

Im Verlauf dieser Analyse möchten wir die folgenden Forschungsfragen beantworten:

Wie beeinflusst das Wetter die Nutzung von Fahrradverleihdiensten?
Welche sind die Hauptstoßzeiten für den Fahrradverleih?
Wie variieren die Nutzungsmuster von Fahrradverleihdiensten im Tages-, Wochen- und Jahresverlauf?
Wie unterscheidet sich das Verhalten von registrierten und gelegentlichen Nutzern?
Wie genau können wir zukünftige Nutzungsmuster basierend auf historischen Daten vorhersagen?

## Verwendete Bibliotheken

Dieses Projekt nutzt eine Reihe von Python-Bibliotheken, darunter:

- pandas: Datenmanipulation und -analyse
- numpy: Unterstützung für große, mehrdimensionale Arrays und Matrizen
- matplotlib und seaborn: Datenvisualisierung
- scikit-learn: Werkzeuge für maschinelles Lernen und Modellentwicklung
- Jupyter: Erstellen und Teilen von Notebooks


## Zukünftige Pläne

Das Fahrradverleih-Geschäft wächst rasant und stellt ständig neue Herausforderungen und Möglichkeiten. Mit Blick auf die Zukunft, könnten folgende Erweiterungen und Verbesserungen unser Projekt noch wertvoller für Unternehmen in der Branche machen:

1. **Einbeziehung stündlicher Daten:** Die bisherige Analyse konzentriert sich auf tägliche Muster. Durch die Einbeziehung stündlicher Daten könnten wir detailliertere Erkenntnisse über die Fahrradnutzung im Tagesverlauf gewinnen. Diese Informationen könnten Unternehmen dabei helfen, ihre Flotten effizienter zu verwalten und sicherzustellen, dass genügend Fahrräder während Stoßzeiten zur Verfügung stehen.

2. **Erweiterung auf andere Städte oder Regionen:** Derzeit basiert unser Modell auf Daten aus Washington D.C. Eine Erweiterung auf andere Städte oder Regionen würde es uns ermöglichen, lokalspezifische Nutzungsmuster zu analysieren und zu vergleichen, was für Unternehmen von Interesse sein könnte, die in mehreren Märkten tätig sind oder expandieren möchten.

3. **Integration von Echtzeit-Wetterdaten:** Unser aktuelles Modell berücksichtigt Wetterdaten, aber eine Integration von Echtzeit-Wetterdaten könnte die Vorhersagegenauigkeit verbessern. Dies könnte besonders nützlich sein, um kurzfristige Schwankungen in der Fahrradnutzung zu verstehen und darauf zu reagieren.

4. **Untersuchung der Auswirkungen von Ereignissen:** Große Veranstaltungen, Straßenarbeiten oder andere besondere Umstände können einen erheblichen Einfluss auf die Fahrradnutzung haben. Eine zukünftige Erweiterung könnte versuchen, solche Ereignisse in das Modell zu integrieren, um seine Vorhersagekraft weiter zu verbessern.

5. **Integration von E-Bike-spezifischen Daten:** E-Bikes stellen einzigartige Herausforderungen und Möglichkeiten im Vergleich zu herkömmlichen Fahrrädern dar, wie z.B. die Notwendigkeit des Ladens und erhöhte Reichweiten. Eine Analyse, die E-Bike-spezifische Daten berücksichtigt, könnte dabei helfen, spezifische Strategien für diesen wachsenden Sektor zu entwickeln.
