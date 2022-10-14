# Umfrage

- Speichern Sie dieses Repository als ZIP-Datei auf Ihrem Rechner.

![](references/img/github.png)

- Entpacken Sie die Datei in einen Ordner Ihrer Wahl.

- Öffnen Sie Visual Studio Code und wählen Sie oben links in der Aktivitätsleiste  „Explorer“ aus. Navigieren Sie zu dem blauen Menüpunkt "Open Folder" und wählen Sie den Ordner "umfrage" aus. Dieser Ordner ist nun Ihr Projektverzeichnis.

![](references/img/vscode.png)


- Öffnen Sie im Explorer den Ordner "notebooks" und öffnen Sie die Datei `01-JK-data-preparation.ipynb`

## Projektstruktur

Für dieses Projekt sind nur die folgenden beiden Ordner relevant:  

- **data**
- **notebooks**
- **references**


```nohighlight
├── README.md          <- The top-level README for people using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `01-JK-data-preparation.ipynb`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g. a `environment.yml` file
```

Die Projektstruktur orientiert sich an dem von DrivenData bereitgestellten [Cookiecutter Data Science-Template](https://drivendata.github.io/cookiecutter-data-science/)
