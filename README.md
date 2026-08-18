# Workshop "Einführung in Python" 

Der Workshop "Einführung in Python" richtet sich insbesondere an Python-AnfängerInnen und es werden keine Python- oder Programmier-Kenntnisse vorausgesetzt. 

Konzipiert wurde der Workshop im Rahmen des FDM-Curriculums der UA Ruhr. 

## Ausführung 

Die einfachste Möglichkeit, um Python auszuprobieren -- und den Workshop-Code auszuführen -- ist die Verwendung eines Jupyter-Hubs. 

### JupyterHub der NFDI

Die komfortabelste Lösung bietet der Jupyter-Hub der [NFDI](https://www.nfdi.de/). 
Klicken Sie einfach auf das folgende Logo, um sich anzumelden und den Workshop-Code und die notwendigen Dateien im NFDI-Jupyter-Hub zu nutzen: 

[![Jupyter4NFDI](https://nfdi-jupyter.de/images/jupyter4nfdi_badge.svg)](https://hub.nfdi-jupyter.de/v2/gh/berndzey/python-einfuehrung-workshop-fdm/main?labpath=python-workshop-fdm-template.ipynb&system=deNBI-Cloud&flavor=m1&localstoragepath=%2Fhome%2Fjovyan%2Fwork)


### Jupyterhub.nrw

Sie können den Code analog auch auf dem Jupyterhub.nrw laufen lassen. Das Problem ist, dass der Server von Ihrer Institution abhängt und ein allgemeiner Link wie bei der NFDI nicht möglich ist. Für die TU Dortmund lautet der Link wie folgt: 
`https://tu-dortmund.jupyterhub.nrw/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fberndzey%2Fpython-einfuehrung-workshop-fdm&urlpath=lab%2Ftree%2Fpython-einfuehrung-workshop-fdm%2Fpython-workshop-fdm-template.ipynb&branch=main`

-> [Workshop auf Jupyterhub.nrw für die TU Dortmund](https://tu-dortmund.jupyterhub.nrw/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fberndzey%2Fpython-einfuehrung-workshop-fdm&urlpath=lab%2Ftree%2Fpython-einfuehrung-workshop-fdm%2Fpython-workshop-fdm-template.ipynb&branch=main)

Für Ihre Institution müssen Sie den Anfangsteil `tu-dortmund` mit Ihrem Institutionskürzel ersetzen; dann sollte der Link funktionieren. 

Alternativ können Sie natürlich selber ein Projekt auf [Jupyterhub.nrw](https://www.jupyterhub.nrw/de/) erstellen und den Code und die Dateien hochladen. 

### Lokale Ausführung

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

