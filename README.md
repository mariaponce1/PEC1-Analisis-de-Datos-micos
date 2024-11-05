# Análisis de Metabolómica en R
Este repositorio contiene el análisis de un dataset de metabolómica (el archivo que he subido como .txt) usando R y el paquete `SummarizedExperiment`.

## Contenido
- `Ponce-Renilla-Maria-PEC1.html`: informe de la práctica en formato HTML.
- `contenedor_datos_y_metadatos.Rda`: objeto `SummarizedExperiment` que contiene los datos y metadatos organizados.
- `codigo_analisis.R`: código R usado para realizar el análisis.
- `DataValues_S013.txt`: datos que se han usado para realizar este análisis. 

## Descripción del Dataset
El dataset contiene variables metabolómicas de pacientes, incluyendo:
- **SURGERY**: Tipo de cirugía (`0` = tubular, `1` = bypass).
- **GENDER**: Género del paciente (`0` = masculino, `1` = femenino).
- **Variables metabolómicas**: Medidas como `GLU_T0` (glucosa), `INS_T0` (insulina), y aminoácidos.

## Requisitos
Para reproducir este análisis, instala los siguientes paquetes de R:
```r
install.packages("ggplot2")
BiocManager::install("SummarizedExperiment")
BiocManager::install("pheatmap")
