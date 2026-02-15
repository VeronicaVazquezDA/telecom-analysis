# 📊 ConnectaTel - Telecom Customer Behavior Analysis

## 📌 Objetivo del Proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica, con el fin de:

- Evaluar patrones de uso de llamadas y mensajes.
- Identificar segmentos de clientes según edad y nivel de consumo.
- Detectar posibles inconsistencias en los datos.
- Analizar oportunidades de mejora en la oferta actual de planes.
- Generar recomendaciones estratégicas basadas en evidencia.

Este análisis busca aportar insights accionables que ayuden a optimizar la propuesta de valor de la empresa.

---

## 📂 Datasets Utilizados

El proyecto utiliza tres archivos principales:

### 1️⃣ `plans.csv`
Contiene información sobre los planes disponibles:
- Precio mensual
- Minutos incluidos
- Mensajes incluidos
- GB incluidos
- Costo por consumo adicional

### 2️⃣ `users.csv`
Información demográfica y contractual de los clientes:
- `user_id`
- Edad
- Ciudad
- Fecha de registro
- Plan contratado
- Fecha de cancelación (churn)

### 3️⃣ `usage.csv`
Detalle del uso real del servicio:
- Llamadas realizadas
- Duración total de llamadas (minutos)
- Mensajes enviados
- Fecha de actividad

---

## 🔎 Etapas del Análisis

El proyecto se desarrolló en las siguientes etapas:

### 1️⃣ Exploración inicial de datos (EDA)
- Revisión de estructura y tipos de datos
- Identificación de valores nulos
- Detección de valores erróneos (ej. -999 en edad, fechas fuera de rango)
- Validación de integridad de `user_id`

### 2️⃣ Limpieza y preparación
- Corrección de valores inválidos
- Tratamiento de datos faltantes
- Eliminación o ajuste de registros inconsistentes
- Consolidación de datasets

### 3️⃣ Análisis descriptivo
- Distribución de edad por tipo de plan
- Análisis de mensajes enviados
- Análisis de llamadas realizadas
- Análisis de duración total de llamadas
- Identificación de outliers

### 4️⃣ Segmentación
- Segmentación por edad
- Segmentación por nivel de uso (bajo, medio, alto consumo)
- Identificación de patrones relevantes para negocio

### 5️⃣ Conclusiones y recomendaciones
- Evaluación de la alineación entre consumo real y beneficios incluidos
- Identificación de oportunidades de mejora en los planes
- Propuestas estratégicas para optimización de oferta

---

## ▶️ Cómo Ejecutar el Notebook

### Opción 1: Google Colab (Recomendado)

1. Subir el archivo `.ipynb` a Google Drive.
2. Abrir con Google Colab.
3. Subir los archivos `plans.csv`, `users.csv` y `usage.csv` al entorno de Colab.
4. Ejecutar las celdas en orden.

### Opción 2: Entorno Local (Jupyter Notebook)

1. Clonar este repositorio:
2. 2. Instalar librerías necesarias:
- pandas
- numpy
- matplotlib
- seaborn

3. Abrir Jupyter Notebook:
4. 4. Ejecutar el archivo `.ipynb` en orden secuencial.

---

## 🔁 Guía de Reproducción

Para reproducir el análisis correctamente:

1. Colocar los tres archivos CSV en el mismo directorio que el notebook.
2. Ejecutar las celdas en orden (no saltar pasos de limpieza).
3. Verificar que no existan errores de rutas.
4. Revisar las secciones de visualización y conclusiones finales.

El análisis es completamente reproducible siempre que se utilicen los mismos datasets originales.

---

## 📈 Principales Hallazgos

- No existe una relación fuerte entre edad y tipo de plan contratado.
- La mayoría de los usuarios presenta bajo consumo de llamadas y mensajes.
- Los planes actuales incluyen beneficios superiores al uso real promedio.
- Se identificaron oportunidades para rediseñar planes más alineados al comportamiento actual del cliente.

---

## 💡 Impacto del Proyecto

Este análisis demuestra cómo el uso de datos permite:

- Detectar ineficiencias en la oferta de productos.
- Identificar segmentos estratégicos.
- Proponer mejoras basadas en evidencia.
- Generar insights accionables para toma de decisiones.

---

## 👩‍💻 Autora

Proyecto desarrollado como práctica de análisis de datos enfocado en segmentación y evaluación de comportamiento de clientes en telecomunicaciones.

