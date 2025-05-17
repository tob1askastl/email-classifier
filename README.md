# Bachelorarbeit – Phishing-Erkennung mit Machine Learning

Dieses Repository enthält den Code und die begleitenden Dateien.

## Projektstruktur

- `EmailClassifier/notebooks/email_classification.ipynb`: Notebook für Datenvorverarbeitung, Feature-Analyse, Modelltraining und Evaluation
- `EmailClassifier/data/`: Enthält Trainings- und Testdaten, bestehend aus CSV-Dateien sowie realen E-Mails im `.eml`-Format
- `email_classifier.html`: Exportierter "Snapshot" eines vollständigen Durchlaufs, das auch als Grundlage für die Analyse in der schriftlichen Arbeit diente

## Installation / Abhängigkeiten

Zur Ausführung des Notebooks werden folgende Python-Bibliotheken benötigt:

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost
- jupyter (lokale Ausführung im Browser mit `jupyter notebook`)

Die Abhängigkeiten können mit folgendem Befehl installiert werden:

```bash
pip install -r requirements.txt
```

Note: die Ausgaben können bei der Ausführung variieren. Die Analyse in der Bachelorarbeit basiert auf dem exportierten Snapshot `email_classifier.html`.