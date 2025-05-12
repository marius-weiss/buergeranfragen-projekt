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
├── environment.yml       # Conda-Umgebungsdatei mit Paketliste
└── README.md             # Dieses Dokument
```

---

## Entwicklungsumgebung (Conda)

Dazu bitte zunächst Anaconda installieren: https://www.anaconda.com/download 

### Einrichtung mit Anaconda (empfohlen)

1. Neue Umgebung erstellen:
```bash
conda create -n buergeranfragen python=3.10
```

2. Umgebung aktivieren:
```bash
conda activate buergeranfragen
```

3. Pakete installieren:
```bash
conda install pandas matplotlib seaborn scikit-learn nltk spacy
```

4. Deutsches Sprachmodell für spacy laden:
```bash
python -m spacy download de_core_news_sm
```

### Wiederherstellung der Umgebung mit folgendem Befehl
```bash
conda env create -f environment
```



