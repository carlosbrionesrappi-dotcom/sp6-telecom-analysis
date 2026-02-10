# 📊 Análisis de Comportamiento de Clientes – ConnectaTel (Sprint 7)

Este repositorio contiene un análisis de datos exhaustivo sobre **ConnectaTel**, una empresa de telecomunicaciones en Latinoamérica. El proyecto se enfoca en evaluar el comportamiento de los clientes, detectar patrones de consumo y generar segmentos estratégicos basándose en datos registrados hasta el año **2024**.

---

## 🚀 Objetivo del Análisis

* **Gobernanza de Datos:** Limpieza y normalización de datasets de planes, usuarios y consumo.
* **Calidad de Datos:** Identificación de valores atípicos, manejo de valores centinela (como `-999` en edad) y corrección de inconsistencias temporales.
* **Análisis Estadístico:** Construcción de perfiles de consumo para llamadas, mensajes y minutos totales.
* **Segmentación Estratégica:** Clasificación de usuarios por intensidad de uso (Bajo, Medio, Alto) y por grupos generacionales (Joven, Adulto, Adulto Mayor).

---

## 🛠️ Tecnologías y Herramientas

* **Lenguaje:** Python 3.x
* **Librerías principales:** * `Pandas`: Manipulación y limpieza de estructuras de datos.
    * `Matplotlib` & `Seaborn`: Visualización de distribuciones y detección de outliers.
    * `Numpy`: Lógica de segmentación mediante condiciones vectorizadas.
* **Entorno:** Jupyter Notebook / Google Colab.

---

## 📂 Estructura del Proyecto

* `sprint7-final-project.ipynb`: Notebook principal con el flujo de trabajo completo (Exploración, Limpieza, EDA y Segmentación).
* **Datasets utilizados**:
    * `plans.csv`: Tarifas y beneficios por plan.
    * `users.csv`: Datos demográficos y fechas de registro/cancelación.
    * `usage.csv`: Registro de uso real de servicios.

---

## 📊 Resumen de Hallazgos (Insights)

> [!IMPORTANT]
> **Dato Clave:** El **88.35% de los usuarios** se mantienen activos (según nulos en `churn_date`). Se identificó un grupo de "Heavy Users" con consumos de hasta **155.6 minutos**, superando significativamente el promedio.

* **Calidad:** Se detectaron y corrigieron registros con fechas en el año **2026**, asegurando la integridad del análisis hasta 2024.
* **Uso por Plan:** Aunque el plan Básico es el más popular, un porcentaje considerable de sus usuarios muestra un nivel de **"Alto Uso"**, lo que representa una oportunidad de migración a planes Premium.
* **Demografía:** No se encontró una correlación fuerte entre la edad y el volumen de mensajes, desmitificando patrones de consumo generacionales.

---

## 🚀 Cómo utilizar este repositorio

### Opción 1: Google Colab (Recomendado)
Haz clic en el siguiente botón para ejecutar el código directamente en la nube:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([TU_LINK_DE_COLAB_AQUI](https://colab.research.google.com/drive/1DSpHJ3dT72Iylnl24gCCicSD_TVFl0M6))

### Opción 2: Ejecución Local
1. Clona el repositorio:
   ```bash
   git clone [https://github.com/carlosbrionesrappi-dotcom/nombre-del-repo.git](https://github.com/carlosbrionesrappi-dotcom/nombre-del-repo.git)
