# edo
Questa repo contiene i file e le istruzioni per svolgere corsi di robotica educativa utilizzando gli e.DO COMAU.

## Requisiti
Controlla di avere installato Python (versione 3 o superiore) e Pip. Per esempio, su Mac o Linux:

        python --version
        pip --version

## Allestimento ambiente virtuale
Un ambiente virtuale consente di installare e gestire librerie esterne in maniera isolata e sicura. Per questo progetto, usiamo Anaconda.

1. [Installa Anaconda Navigator](https://www.anaconda.com/products/distribution)
2. Importa un nuovo ambiente
    - Vai su Environments 
    - Clicca su Import
    - Scegli Local Drive e seleziona il file `edo-env.yaml` (presente in questa repository)
    - Clicca su Import
3. Attiva l'ambiente virtuale: 
    - Clicca sul tasto play dell'ambiente `edo-env`

# RoboPython
Corso per imparare a movimentare l'e.DO utilizzando la liberia Python `pyedo`.

Per accedere all'ambiente di sviluppo:

1. Attiva l'ambiente (vedi sezione precedente)
2. In Home, avviare Jupyter Notebook
3. Navigare alla cartella contenente il file `robopython.ipynb`