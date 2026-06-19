# Proyecto_6_Analisis_Connectatel
# Análisis Exploratorio de Clientes de ConnectaTel

##  Objetivo del Proyecto

El objetivo de este proyecto es realizar un análisis exploratorio de los clientes de ConnectaTel con el fin de identificar segmentos de usuarios, detectar patrones de uso, encontrar valores extremos y generar recomendaciones para mejorar la oferta actual de planes.

---

##  Dataset Utilizado

Se trabajó con un conjunto de datos que contiene información sobre los clientes y su comportamiento de uso, incluyendo variables como:

- `age`: edad del usuario.
- `plan`: tipo de plan contratado.
- `cant_mensajes`: cantidad de mensajes enviados.
- `cant_llamadas`: cantidad de llamadas realizadas.
- `total_minutos_llamada`: total de minutos consumidos en llamadas.

---

##  Etapas del Análisis

- Exploración inicial de los datos.
- Identificación y tratamiento de valores inválidos y faltantes.
- Análisis de distribuciones mediante histogramas.
- Detección de valores extremos utilizando boxplots y el método IQR.
- Segmentación por grupo de edad y nivel de uso.
- Análisis de variables categóricas.
- Elaboración de conclusiones y recomendaciones para el negocio.

---

##  Cómo Ejecutar el Notebook

### Opción 1: Google Colab

1. Descargar el archivo `.ipynb`.
2. Abrir Google Colab.
3. Seleccionar **Archivo → Subir notebook**.
4. Ejecutar las celdas en orden.

### Opción 2: Jupyter Notebook

Instalar las librerías necesarias:

```bash
 pandas numpy matplotlib seaborn
```

Ejecutar Jupyter Notebook:

```bash
jupyter notebook
```

Abrir el archivo `.ipynb` y ejecutar las celdas secuencialmente.

---

##  Guía de Reproducción

1. Cargar el dataset.
2. Realizar la limpieza y validación de los datos.
3. Generar histogramas y boxplots.
4. Crear las variables `grupo_uso` y `grupo_edad`.
5. Analizar los resultados obtenidos.
6. Revisar las conclusiones y recomendaciones.

---

## 📌 Principales Hallazgos

- La mayoría de los clientes pertenece al segmento de uso medio.
- Los adultos representan el grupo de edad predominante.
- Existen usuarios con consumos extremos que podrían requerir planes especializados.
- Los jóvenes representan una oportunidad de crecimiento para ConnectaTel.
- Los usuarios de alto consumo constituyen un segmento estratégico para desarrollar planes premium.
