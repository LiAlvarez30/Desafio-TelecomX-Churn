# 📡 Telecom X: Data Pipeline & Churn Analytics
> **Transformando datos crudos en estrategias de retención de clientes.**

---

## 🚀 El Desafío: ¿Por qué se van los clientes?
Telecom X enfrentaba una fuga crítica de usuarios. Como parte de este proyecto, construí un flujo de trabajo profesional para extraer, limpiar y analizar el comportamiento de **7,032 clientes**. El objetivo fue encontrar los "puntos de ruptura" que explican por qué el **26.6%** de la base decide cancelar su servicio.

---

## 🛠️ Stack Tecnológico
Para asegurar la calidad de este análisis, utilicé las herramientas estándar de la industria:
* **Lenguaje:** Python 3.12 🐍
* **Manipulación de Datos:** Pandas (ETL & Data Wrangling) 📊
* **Visualización:** Seaborn & Matplotlib (Análisis Estadístico) 📈
* **Ingestión:** Requests (Consumo de API JSON) 🌐

---

## 🏗️ Arquitectura del Proyecto (Pipeline ETL)
El proyecto sigue un proceso riguroso de ingeniería de datos:

1. **Extracción (Extract):** Ingestión de datos desde una API externa en formato JSON.
2. **Transformación (Transform):**
    * **Aplanamiento:** Conversión de estructuras anidadas a un DataFrame plano.
    * **Limpieza:** Tratamiento de inconsistencias y eliminación de valores nulos.
    * **Feature Engineering:** Creación de la métrica `cargos_diarios` para análisis de micro-gasto.
3. **Análisis (EDA):** Identificación de patrones de evasión mediante visualizaciones avanzadas.

---

## 💡 Hallazgos Críticos (Insights de Negocio)

A través del análisis, detectamos que el perfil de **máximo riesgo** de fuga cumple con estas características:

| Variable | Segmento de Alto Riesgo | Impacto Observado |
| :--- | :--- | :--- |
| **Contrato** | Mes a Mes | Mayor volumen de bajas (**1,655 casos**) |
| **Tecnología** | Fibra Óptica | Tasa de evasión superior al DSL (**1,297 casos**) |
| **Pago** | Cheque Electrónico | Método con mayor deserción (**1,071 casos**) |
| **Soporte** | Sin Soporte Técnico | Punto crítico de pérdida de lealtad (**1,446 casos**) |

### 🧠 Correlación Matemática
La matriz de correlación confirmó que la **permanencia (meses_contrato)** tiene una relación negativa de **-0.35** con la evasión. Esto significa que los primeros **6 meses** son la "zona roja" donde la probabilidad de fuga es más alta.

---

## ⚙️ Cómo Ejecutar este Proyecto
1. Clona el repositorio:
   ```bash
   git clone https://github.com/LiAlvarez30/Desafio-TelecomX-Churn.git


## 👨‍💻 Autor
**Liliana Alvarez** *Data Engineer / Analyst*

> "Los datos no mienten, pero hay que saber preguntarles."
