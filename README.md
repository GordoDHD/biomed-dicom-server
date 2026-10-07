# Server PACS/DICOM con Docker e Orthanc

Progetto per il deployment di un server PACS (Picture Archiving and Communication System) basato su Orthanc, containerizzato tramite Docker Compose per la gestione e archiviazione di immagini diagnostiche DICOM (`.dcm`).

## Struttura del Progetto
* `docker-compose.yml`: Configurazione del container e dei volumi di persistenza.
* `orthanc.json`: Parametri di rete e credenziali di autenticazione del server.
* `sample-data/`: Cartella per il caricamento dei dataset di test.

## Requisiti
* Docker Engine / Docker Desktop
* Docker Compose

## Come Avviarlo
1. Clona la repository:
   ```bash
   git clone [https://github.com/GordoDHD/biomed-dicom-server.git](https://github.com/GordoDHD/biomed-dicom-server.git)
