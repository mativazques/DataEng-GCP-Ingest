# Práctica ingest GCP 

### Consignas

1) Crear un bucket regional standard, en Finlandia y llamado demo-bucket-edvai.
1) Crear un bucket multi regional standard, en Estados Unidos y llamado demo-bucket-demo-1.  
2) Hacer ingest con la herramienta CLIO GSutil de 5 archivos csv en el bucket data-bucket-demo-1. 
3) Utilizar el servicio transfer para crear un job que copie los archivos que se encuentran en data-bucket-demo-1 a data-bucket-edvai. 

### Resultados 

Se puede sintetizar todas las resoluciones a un script de bash para simplificar el proceso, el archivo es [ingest_gsutil.sh](ingest_gsutil.sh).

El archivo donde se muestra el procedimiento es [Trabajo_5_ingest_GCP.pdf](Trabajo_5_ingest_GCP.pdf). 
