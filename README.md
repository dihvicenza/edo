# edo
Questa repo contiene i file e le istruzioni per svolgere corsi di robotica educativa utilizzando gli e.DO COMAU e Python.

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
    - Scegli Local Drive e seleziona il file `edo-env.yaml` (se su MacOs) o `win-edo.yml` (se su Windows)
    - Clicca su Import
3. Attiva l'ambiente virtuale: 
    - Clicca sul tasto play dell'ambiente `edo-env`
    - Clicca "Open with Jupyter Notebook"

# RoboPython
Corso per imparare a movimentare l'e.DO utilizzando la libreria [pyedo](https://github.com/Comau/pyedo).

Per accedere all'ambiente di sviluppo:

1. Dopo aver impostato l'e.DO (es. da tablet), *disconnetti tutti i dispositivi*.
2. Disconnetti il tablet o altri dispositivi *anche dal Wi-Fi dell'e.DO*.
3. Sul PC, connettiti al Wi-Fi dell'e.DO. Nota che perderai accesso a internet da questo dispositivo.
4. Apri Anaconda Navigator e attiva l'ambiente (vedi sezione precedente).
5. Nella sezione Home, avvia Jupyter Notebook.
6. Naviga alla cartella contenente il file `robopython.ipynb` e apri. Segui le istruzioni di connessione.

## Risorse

- https://github.com/Comau/pyedo
