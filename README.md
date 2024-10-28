# DSA_Proyecto_AccidentesTransito
Este repositorio está diseñado para desarrollar y analizar un producto de analítica de datos enfocado en la problemática de accidentes de tránsito en Estados Unidos. El proyecto tiene como objetivo construir un modelo predictivo que permita anticipar la ocurrencia de accidentes de tránsito utilizando datos históricos y contextuales. Con ello, se busca desarrollar una herramienta para diseñar estrategias preventivas y efectivas.

## Estructura del Repositorio
El repositorio está organizado en las siguientes carpetas:

- Data/: Contiene los datos utilizados en el proyecto.
    US_Accidents_March23.csv: Este archivo CSV contiene el conjunto de datos utilizado el cual es de acceso público y se encuentra disponible en la plataforma Kaggle. La información se recopila mediante APIs que integran datos de múltiples fuentes, como sensores IoT, cámaras de video y reportes de los departamentos de transporte estatales.
  - Número de Observaciones: 7,7 millones
  - Número de Variables: 46
  - Cobertura Temporal: Febrero de 2016 - Marzo de 2023
  - Cobertura Geográfica: 49 estados de Estados Unidos 
    
- Code/: Incluye los scripts y notebooks utilizados para el análisis.
    
- Results/: Esta carpeta almacena los resultados preliminares del análisis, tales como gráficos, tablas y cualquier otro resultado derivado del notebook.

- Document/: Aquí se encuentran los docuemntos realcionados en formato PDF.

## Instrucciones de Uso
- Clonar el repositorio:
    git clone (https://github.com/jsmoralesc/DSA_Proyecto_AccidentesTransito.git)
- Navegar a la carpeta Code/ para revisar y ejecutar el análisis.
- Explorar los resultados en la carpeta Results/ para ver los gráficos y tablas generados.
- Revisar los documentosen  carpeta Document/ para entender el contexto y objetivos del proyecto.

## Requisitos
- Python 3.13.0
- Jupyter Notebook
- Librerías: pandas, numpy, matplotlib, seaborn, scikit-learn, dvc
- Para instalar las dependencias necesarias, puedes utilizar el siguiente comando: pip install -r requirements.txt
