# Proyecto_6_Analisis_Connectatel
Análisis Exploratorio de Clientes de ConnectaTel
Objetivo del Proyecto

El objetivo de este proyecto es realizar un análisis exploratorio de los clientes de ConnectaTel con el fin de identificar segmentos de usuarios, detectar patrones de uso, encontrar valores extremos y generar recomendaciones que permitan mejorar la oferta actual de planes y desarrollar nuevos productos adaptados a las necesidades de los clientes.

Datasets Utilizados

Se trabajó con un conjunto de datos que contiene información de los clientes y su comportamiento de uso, incluyendo variables como:

age: edad del usuario.
plan: tipo de plan contratado.
cant_mensajes: cantidad de mensajes enviados.
cant_llamadas: cantidad de llamadas realizadas.
total_minutos_llamada: total de minutos consumidos en llamadas.
Otras variables relacionadas con el perfil y el uso del servicio.
Etapas del Análisis
Exploración inicial de los datos.
Identificación y tratamiento de valores inválidos y faltantes.
Análisis de distribuciones mediante histogramas.
Detección de valores extremos utilizando boxplots y el método IQR.
Creación de segmentos por nivel de uso y grupo de edad.
Análisis de variables categóricas mediante gráficos de barras.
Interpretación de resultados y formulación de recomendaciones para el negocio.
Cómo Ejecutar el Notebook
Opción 1: Google Colab
Descargar el archivo .ipynb.
Abrir Google Colab.
Seleccionar Archivo → Subir notebook.
Ejecutar las celdas en orden.
Opción 2: Jupyter Notebook
Clonar el repositorio.
Instalar las dependencias necesarias:
pip install pandas numpy matplotlib seaborn
Abrir Jupyter Notebook:
jupyter notebook
Abrir el archivo .ipynb y ejecutar las celdas secuencialmente.
Guía de Reproducción
Cargar los datasets.
Ejecutar la etapa de limpieza y validación de datos.
Generar los histogramas y boxplots para explorar las distribuciones.
Crear las variables de segmentación (grupo_uso y grupo_edad).
Analizar los gráficos y los resultados obtenidos.
Revisar las conclusiones y recomendaciones para ConnectaTel.
Principales Hallazgos
La mayoría de los clientes pertenece al segmento de uso medio.
Los adultos representan el grupo de edad predominante.
Existen usuarios con consumos extremos que podrían requerir planes especializados.
El segmento joven representa una oportunidad de crecimiento para la empresa.
Los usuarios de alto consumo constituyen un segmento estratégico para desarrollar planes premium.
