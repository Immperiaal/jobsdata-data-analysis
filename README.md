# jobsdata-data-analysis
## 🇪🇸 Descripción
En este repositorio, exploramos un dataset sobre los distintos salarios en el mundo del Big Data. El propósito de este estudio es analizar el mercado del Big Data actual, y como difieren ciertas característcas como el salario, tipo de empresa, presencialidad, etc.

## Características
- **Extracción de datos**: Conexión y extracción de datos desde una API de datos meteorológicos.
- **Tranformación de datos**: Seleccionamos rigurosamente los campos de interés.
- **Visualización de datos**: Transferencia de datos seleccionados a una base de datos PostgreSQL.

## Requisitos
- El dataset de datajobs (/data).
- Un servidor de base de datos PostgreSQL, puede optar por otras altenativas.
- Un fichero con las credenciales de la base de datos y del email.
- Un email con su respectiva app password.

## Contribución
Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cualquier cambio importante antes de realizarlo.

## 🇬🇧 Description
In this repository, we explore the use of Airflow for extracting weather data and alerts from an API, and loading them into a PostgreSQL database. Additionally, we automate this process to ensure tasks are executed on schedule. In case of success or failure, the user will be notified via email. Under the dags/ folder, you can find:
- **DAG_Weather_Alerts_API.py**: Extraction and loading of weather alerts, and notification to the user in case alerts exist or in case of execution failure.
- **DAG_Weather_API.py**: Extraction and loading of weather data, and notification to the user upon successful data loading or in case of execution failure.

## Features
- **Data Extraction**: Connection and extraction of data from a weather data API.
- **Data Transformation**: Careful selection of fields of interest.
- **Data Loading**: Transfer of selected data to a PostgreSQL database.
- **Automation**: DAG configuration to automate the extraction and loading process.
- **Notification**: Notification of successful or failed status via email.

## Requirements
- A functional Airflow service.
- A PostgreSQL database server; other alternatives can also be considered.
- A file containing credentials for the database and email.
- An email with its respective app password.

## Contribution
Contributions are welcome. Please open an issue to discuss any major changes before implementing them.
