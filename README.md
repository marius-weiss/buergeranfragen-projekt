# Projekt: Automatisierte Analyse und Kategorisierung von Bürgeranfragen

## Projektidee
Ziel dieses Projekts ist es, mithilfe von Natural Language Processing (NLP) ein Modell zu entwickeln, das automatisch Bürgeranfragen analysiert und in vordefinierte Kategorien (z. B. „Abfall“, „Straßenbeleuchtung“, „Bauantrag“) einordnet.

So soll die Effizienz in der öffentlichen Verwaltung gesteigert und die Bearbeitung von Anliegen erleichtert werden.

---

## Projektstruktur

```
buergeranfragen-projekt/
│
├── data/                 # Daten
│   ├── raw/              # Originaldaten (CSV, unbearbeitet)
│   └── processed/        # Vorverarbeitete Daten (z. B. TF-IDF)
│
├── notebooks/            # Jupyter Notebooks für Analyse & Modellierung
│   ├── 01_analysis.ipynb
│   └── 02_modelling.ipynb
│
├── models/               # Gespeicherte Modelle (z. B. .pkl oder .joblib)
│
├── outputs/
│   ├── figures/          # Visuals: Diagramme, Plots, Wortwolken
│   └── results/          # Evaluation: Scores, Metriken, Tabellen
│
├── reports/              # Studienarbeit (IEEE-Format)
│
├── src/                  # Python-Skripte: Preprocessing, Training etc.
│
├── requirements.txt      # Liste aller Python-Abhängigkeiten
└── README.md             # Dieses Dokument
```

---

## Voraussetzungen

- Python 3.10+
- Empfohlene Tools:
  - Anaconda
  - JupyterLab
  - VS Code
  - Alternativ: Google Colab

### Wichtige Pakete
```bash
pip install pandas scikit-learn matplotlib seaborn nltk spacy
```

---

## Erste Schritte

1. Erstelle einen Beispiel-Datensatz in `data/raw/`
2. Starte mit der Datenanalyse in `notebooks/01_analysis.ipynb`
3. Baue dein Modell in `notebooks/02_modelling.ipynb`
4. Dokumentiere Ergebnisse in `reports/`
5. Exportiere Plots nach `outputs/`

---

