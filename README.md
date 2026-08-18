# Workshop "Einführung in Python" 

Der Workshop "Einführung in Python" richtet sich insbesondere an Python-AnfängerInnen und es werden keine Python- oder Programmier-Kenntnisse vorausgesetzt. 

Konzipiert wurde der Workshop im Rahmen des FDM-Curriculums der UA Ruhr. 

## Ausführung 

Die einfachste Möglichkeit, um Python auszuprobieren -- und den Workshop-Code zu bearbeiten -- ist die Verwendung eines Jupyter-Hubs. 
Hierfür bietet sich der Jupyter-Hub der [NFDI](https://www.nfdi.de/) an. 
Klicken Sie einfach auf das folgende Logo, um sich anzumelden und den Workshop-Code und die notwendigen Dateien im NFDI-Jupyter-Hub zu nutzen: 

[![Jupyter4NFDI](https://nfdi-jupyter.de/images/jupyter4nfdi_badge.svg)]([https://hub.nfdi-jupyter.de/v2/gh/_repoowner_/_repotype_/_ref_](https://hub.nfdi-jupyter.de/v2/gh/berndzey/python-einfuehrung-workshop-fdm/main?labpath=python-workshop-fdm-template.ipynb&system=deNBI-Cloud&flavor=m1&localstoragepath=%2Fhome%2Fjovyan%2Fwork))

Natrülich können Sie den Code auch lokal ausführen. 
Hierfür müssen Sie sich Python installieren und den Code (die zwei JupyterLab-Notebooks) und die Dateien (zwei csv's und eine xlsx) herunterladen. 

## Code

- `python-workshop-fdm-template.ipynb` JupyterLab-Notebook Template (nur Kommentare, wird im Workshop Live mit Code gefüllt)
- `python-workshop-fdm-full.ipynb` Vollständig ausgefülltes JupyterLab-Notebook
- Lizenz: Die JupyterLab-Notebooks sind unter der MIT Lizenz veröffentlicht (siehe License.txt)

## Dateien

- Sie benötigen alle 3 Dateien (csv, xlsx und tab-csv)
- Als .csv-Datei: `Titanic-Dataset.csv`
- Als .xlsx-Datei: `Titanic-Dataset.xlsx`
- Als tab-csv-Datei: `Titanic-Dataset-Tab.csv`
- Spalten-Überschriften
  - PassengerId: zugewiesene ID
  - Survived: Überlebt 0/1
  - Pclass: Ticket-Kategorie First/Second/Third
  - Name: Nachname, Vorname
  - Sex: Geschlecht male/female
  - Age: Alter
  - SibSp: Anzahl Geschwister/Ehepartner an Bord
  - Parch: Anzahl Eltern/Kinder an Bord
  - Ticket: Ticket-Nummer
  - Fare: Ticket-Preis
  - Cabin: Kabinennummer
  - Embarked: Einstiegs-Hafen, C: Cherbourg, Q: Queenstown, S: Southampton

Hinweis: Die csv-Datei ist lizensiert unter CC0 1.0, veröffentlicht auf [https://www.kaggle.com/datasets/yasserh/titanic-dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset). 
Die xlsx- und tab-csv-Datei wurden von Bernd Zey erzeugt und sind unter CC0 1.0 lizensiert

