# S7_Project_ConnectaTel
# 📊 Análisis de datos de clientes – ConnectaTel

## 📌 Descripción del proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de **ConnectaTel**, una empresa de telecomunicaciones en Latinoamérica, mediante técnicas de análisis exploratorio de datos (EDA), limpieza de datos y segmentación de clientes.

A partir de tres conjuntos de datos (`plans`, `users` y `usage`), se busca identificar patrones de consumo, características de los usuarios, comportamientos atípicos y oportunidades comerciales que permitan mejorar la oferta de planes y fortalecer las estrategias de fidelización.

El análisis contempla información registrada hasta el año 2024.

## 🎯 Objetivos

- Explorar y comprender la estructura de los conjuntos de datos.
- Identificar y corregir problemas de calidad de datos.
- Analizar las características demográficas de los clientes.
- Identificar patrones de uso de llamadas y mensajes.
- Detectar y evaluar valores atípicos (outliers).
- Segmentar clientes según su edad y nivel de consumo.
- Formular recomendaciones comerciales para optimizar los planes de ConnectaTel.

## 🗂️ Conjuntos de datos

El proyecto utiliza tres datasets principales:

| Dataset | Descripción |
|---|---|
| `plans.csv` | Información de los planes disponibles, precios, minutos y datos incluidos, así como costos adicionales. |
| `users_latam.csv` | Información de los clientes, incluyendo edad, ciudad, fecha de registro, plan contratado y fecha de cancelación. |
| `usage.csv` | Registro del uso de los servicios, incluyendo llamadas, mensajes, duración y fechas de utilización. |

## 🛠️ Herramientas y tecnologías

Para el desarrollo del proyecto se utilizaron las siguientes herramientas:

- **Python:** Lenguaje de programación utilizado para el análisis.
- **Google Colab:** Entorno de desarrollo para ejecutar y documentar el notebook.
- **Pandas:** Manipulación, limpieza y transformación de datos.
- **NumPy:** Operaciones y cálculos numéricos.
- **Matplotlib:** Visualización de datos.
- **Seaborn:** Elaboración de gráficos estadísticos.

## 🔍 Etapas del análisis

El proyecto se desarrolló en las siguientes etapas:

**1. Carga y exploración de datos**
- Importación de los tres datasets.
- Revisión de dimensiones, tipos de datos y estructura general.

**2. Identificación de problemas de calidad**
- Detección de valores nulos.
- Identificación de valores inválidos y datos centinela.
- Revisión de fechas y registros fuera del periodo establecido.

**3. Limpieza y transformación**
- Tratamiento de valores faltantes.
- Corrección de inconsistencias.
- Estandarización de variables y formatos de fecha.

**4. Análisis exploratorio de datos (EDA)**
- Análisis estadístico de las variables.
- Exploración de distribuciones de edad y consumo.
- Comparación del comportamiento de los clientes según su plan.

**5. Detección de valores atípicos**
- Construcción de diagramas de caja (Boxplots).
- Aplicación del método IQR.
- Evaluación de los valores extremos y decisión sobre su conservación.

**6. Segmentación de clientes**
- Clasificación según nivel de uso: bajo, medio y alto.
- Clasificación según edad: jóvenes, adultos y adultos mayores.
- Visualización de los segmentos y sus patrones de comportamiento.

**7. Análisis ejecutivo**
- Identificación de segmentos comerciales relevantes.
- Evaluación de oportunidades de crecimiento y fidelización.
- Propuestas para mejorar los planes actuales y desarrollar nuevas alternativas.

## 📈 Resultados esperados

El análisis permite comprender mejor el comportamiento de los clientes de ConnectaTel y reconocer oportunidades para:

- Diseñar planes ajustados a los diferentes niveles de consumo.
- Identificar usuarios con potencial de migración hacia planes de mayor valor.
- Desarrollar estrategias de retención para clientes de bajo uso.
- Ofrecer paquetes adicionales a usuarios con consumos elevados.
- Mejorar la toma de decisiones comerciales mediante información basada en datos.

## 🚀 Cómo acceder al proyecto

El notebook fue desarrollado y documentado en Google Colab y se encuentra disponible en el siguiente enlace:

👉 **[Abrir proyecto en Google Colab](https://colab.research.google.com/drive/1raeJDCobl1ij8lS2S0Y0TBHvn8juoQQi?usp=sharing)**

Para ejecutar el análisis:

1. Abre el enlace de Google Colab.
2. Inicia sesión con tu cuenta de Google.
3. Crea una copia del notebook en tu Google Drive si necesitas editarlo.
4. Verifica que los archivos CSV (`plans.csv`, `users_latam.csv` y `usage.csv`) estén disponibles en las rutas utilizadas por el notebook (`/datasets/`).
5. Ejecuta las celdas en orden para reproducir el análisis y visualizar los resultados.

**Nota:** Google Colab proporciona el entorno de ejecución, pero los archivos de datos deben estar disponibles para que el notebook pueda ejecutarse correctamente.

## 👨‍💻 Autor

Proyecto desarrollado como parte de un ejercicio práctico de análisis de datos, enfocado en la exploración, transformación y análisis del comportamiento de clientes de una empresa de telecomunicaciones.

**Tecnologías principales:** Python | Pandas | NumPy | Matplotlib | Seaborn | Google Colab

