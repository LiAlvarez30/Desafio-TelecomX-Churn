📡 Telecom X - Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte del Challenge de Data Science del programa Oracle Next Education (ONE). El objetivo principal es identificar los factores que influyen en la pérdida de clientes de una empresa de telecomunicaciones y proponer estrategias basadas en datos para mejorar la retención.

🎯 Propósito del Proyecto

Telecom X enfrenta una tasa de evasión significativa. Este análisis busca procesar datos demográficos, de servicios y financieros para descubrir patrones que expliquen por qué los clientes cancelan sus suscripciones. Los resultados obtenidos servirán como base para que el equipo de ciencia de datos desarrolle modelos predictivos.

🛠️ Tecnologías y Herramientas
Lenguaje: Python 3.12

Bibliotecas: Pandas, Matplotlib, Seaborn, Requests.

Entorno: Google Colab.

Formato de datos: JSON (extraído vía API).

📂 Estructura del Proyecto
Analisis_Churn_TelecomX.ipynb: Cuaderno principal con el proceso de ETL, limpieza y análisis exploratorio (EDA).

README.md: Documentación del proyecto.

TelecomX_Data.json: Datos crudos (consumidos directamente desde la API del challenge).

📊 Insights Principales
A través del análisis visual y estadístico, se identificaron los siguientes puntos críticos:

Tasa de Evasión: El 26.6% de la base de clientes ha abandonado la compañía.

Fuga Temprana: La mayor densidad de cancelaciones ocurre en los primeros 6 meses de contrato.

Impacto del Contrato: Los clientes con contrato mes a mes representan la mayoría de las evasiones (1,655 casos).

Factores de Riesgo: El uso de Fibra Óptica, el pago por Cheque Electrónico y la ausencia de Soporte Técnico son los principales indicadores de una posible evasión.

Correlación Matemática: El tiempo de permanencia (tenure) es la variable con mayor influencia negativa en el Churn (-0.35), confirmando que a mayor lealtad temporal, menor riesgo de fuga.

🚀 Instrucciones para Ejecutar

Para replicar este análisis, sigue estos pasos:

Clona este repositorio:

Bash
git clone https://github.com/LiAlvarez30/Desafio-TelecomX-Churn.git
Sube el archivo .ipynb a Google Colab.

Ejecuta las celdas en orden. El cuaderno descargará automáticamente los datos desde la API oficial.

💡 Conclusiones
Para reducir el churn, Telecom X debe enfocar sus esfuerzos en incentivar la migración a contratos anuales y mejorar la experiencia de soporte técnico en clientes de fibra óptica durante su primer año de servicio.
