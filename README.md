
# Proyecto de ETL y Análisis de Datos con Google Cloud Functions y BigQuery
Este proyecto tiene como objetivo principal extraer, transformar y cargar datos relacionados con servicios de transporte público desde diversas APIs, para luego almacenar los datos en Google Cloud Storage y procesarlos en BigQuery para su análisis posterior.

# Descripción del Proyecto 🚀
Este proyecto de inteligencia de negocios utiliza tecnologías como Google Cloud Functions, BigQuery, y Google Cloud Storage para automatizar el proceso ETL (Extract, Transform, Load). Los datos recolectados desde múltiples APIs son almacenados en Google Cloud Storage y procesados para ser enviados a BigQuery, donde se pueden realizar análisis y consultas para facilitar la toma de decisiones.

# Arquitectura de la Solución 🏗️
Google Cloud Functions: Se encargan de hacer las solicitudes a las APIs, procesar los datos, y guardarlos en Google Cloud Storage y BigQuery.
Google Cloud Storage: Almacena los archivos CSV descargados desde las APIs.
BigQuery: Permite realizar consultas y análisis sobre los datos ya procesados.
Archivos de Código
Función: allp
Esta función obtiene datos de varias APIs de transporte público de Santiago de Chile, procesa la información y la almacena en Google Cloud Storage en formato CSV.
![](https://github.com/Echeverria29/DataGCPFinal/edit/main/ark2.png)

# Pre-requisitos 📋
Google Cloud SDK: Para la administración de tus proyectos en Google Cloud. Puedes descargarlo aquí.
Configuración de Google Cloud Functions y BigQuery.
Permisos en Google Cloud Storage para almacenar los archivos CSV y en BigQuery para realizar consultas.
# Instalación 🔧
Configura tus funciones en Google Cloud Functions.
Crea un bucket en Google Cloud Storage y asegura que las funciones tengan permisos para acceder al bucket.
Configura BigQuery con el dataset correspondiente.
# Ejecución del Proyecto ⚙️
La función allp realizará las solicitudes a las APIs y almacenará los resultados en Google Cloud Storage.
La función f_cole_m descargará archivos CSV y los almacenará también en Google Cloud Storage.
La función data1 procesará los archivos y los enviará a BigQuery.
# Construido con 🛠️
Google Cloud Functions - Para la automatización del proceso ETL.
Google Cloud Storage - Para almacenamiento de los archivos CSV.
BigQuery - Para análisis de los datos.
# Autor ✒️
Orlando Echeverría Hernández
Expresiones de Gratitud 🎁
Comparte este proyecto con otros.
Invita a tus colegas a colaborar en el proyecto.
