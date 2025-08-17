📊 Telecom X - Análisis de Churn (Evasión de Clientes)

📌 Descripción del Proyecto
Este proyecto analiza los patrones de evasión de clientes (Churn) en Telecom X para identificar factores clave que influyen en la cancelación de servicios. El objetivo es proporcionar insights accionables que ayuden a la empresa a reducir la tasa de abandono y mejorar las estrategias de retención de clientes.

🔍 Hallazgos Clave
📈 Principales Métricas
Tasa general de Churn: 26.5%

Clientes con mayor riesgo: Contratos mensuales (42% Churn)

Clientes más leales: Contratos de 2 años (7% Churn)

🎯 Insights Destacados
Los clientes con fibra óptica tienen 3x más probabilidad de abandonar

El 73% de las bajas ocurren en los primeros 20 meses

Los servicios adicionales reducen el Churn en un 15-20%

🛠️ Cómo Usar Este Proyecto
📋 Requisitos
Python 3.8+

Jupyter Notebook

Bibliotecas listadas en requirements.txt

⚙️ Instalación
bash
git clone https://github.com/tu-usuario/telecom-x-churn-analysis.git
cd telecom-x-churn-analysis
pip install -r requirements.txt
🚀 Ejecución
bash
jupyter notebook TelecomX_Churn_Analysis.ipynb
📂 Estructura del Proyecto
text
telecom-x-churn-analysis/
├── data/                   # Datos originales y procesados
│   ├── raw/                # Datos sin procesar
│   └── processed/          # Datos limpios
├── notebooks/              # Jupyter notebooks
│   ├── EDA.ipynb           # Análisis exploratorio
│   └── Modeling.ipynb      # Modelos predictivos
├── reports/                # Reportes y presentaciones
├── src/                    # Código fuente reusable
├── images/                 # Gráficos y visualizaciones
├── README.md               # Este archivo
└── requirements.txt        # Dependencias
📊 Visualizaciones Destacadas
1. Distribución de Churn por Contrato
https://images/churn_by_contract.png

2. Impacto del Tiempo como Cliente
https://images/tenure_vs_churn.png

3. Matriz de Correlación
https://images/correlation_matrix.png

📌 Conclusiones y Recomendaciones
🔎 Hallazgos Principales:
Los contratos a largo plazo reducen el Churn en un 35%

Los clientes con soporte técnico tienen 25% menos probabilidad de abandonar

El método de pago electrónico está asociado con mayor Churn

💡 Recomendaciones:
Incentivar contratos anuales con descuentos del 5-10%

Paquetes de servicios que incluyan soporte técnico

Programa de fidelización para clientes con 18-24 meses de antigüedad

Mejorar la experiencia con pagos electrónicos

🤝 Contribuciones
Las contribuciones son bienvenidas. Siga estos pasos:

Haga fork del proyecto

Cree una rama para su feature (git checkout -b feature/mejora)

Haga commit de sus cambios (git commit -m 'Añade mejora')

Haga push a la rama (git push origin feature/mejora)

Abra un Pull Request

📄 Licencia
Este proyecto está bajo la licencia MIT.

✉️ Contacto: inglisandro97@gmail.com
