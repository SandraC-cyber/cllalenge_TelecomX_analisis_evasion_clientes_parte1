# Challenge_TelecomX_analisis_evasion_clientes_parte1
📊 **Análisis Exploratorio y Modelo Predictivo de Abandono de Clientes**
Este proyecto realiza un análisis exploratorio de datos (EDA) y un proceso ETL para estudiar los factores asociados al abandono de clientes en una empresa de telecomunicaciones.

Finalmente, se entrena un modelo de Regresión Logística para predecir la probabilidad de que un cliente abandone el servicio.

🎯 **Objetivos**
✔️ Identificar los factores clave relacionados con el abandono.
✔️ Analizar patrones de comportamiento en los clientes.
✔️ Construir un modelo predictivo que permita anticipar el abandono.

🔍 **Hallazgos Principales**
📌 Antigüedad → Los clientes con menor tiempo en la empresa tienen mayor riesgo de abandono.

💰 Cargos → Clientes que abandonan suelen tener:

Cargos mensuales más altos.

Cargos totales más bajos que los que permanecen.

📄 Contrato → Los contratos mensuales muestran mayor abandono que los de largo plazo.

🌐 Tipo de Internet → El servicio de fibra óptica se relaciona con más abandonos.

💳 Método de pago → El cheque electrónico está asociado con mayor tasa de abandono.

🔧 Servicios adicionales → No contratar extras (seguridad online, backup, soporte técnico) incrementa la probabilidad de abandono.

👵 Edad → Las personas mayores presentan mayor tasa de abandono.

🤖 Modelo Predictivo
Se entrenó un modelo de Regresión Logística con los siguientes resultados:

🎯 Accuracy: 79,53 %

✅ Precision: 64,33 %

📈 Recall: 51,60 %

📌 **El modelo logra identificar patrones importantes, aunque requiere mejoras para aumentar la detección de casos reales de abandono.**

🛠️ Tecnologías Utilizadas
🐍 Python 3.x

📦 Pandas & NumPy → ETL y procesamiento de datos

📊 Matplotlib & Seaborn → Visualización y análisis exploratorio

🤖 Scikit-learn → Entrenamiento y evaluación del modelo

📂 Estructura del Repositorio
bash
Copiar
Editar
├── data/          # Dataset utilizado
├── notebooks/     # Jupyter Notebooks con el análisis
├── scripts/       # Scripts de ETL y modelado
├── results/       # Gráficas y métricas obtenidas
└── README.md      # Documentación del proyecto
🚀 Próximos Pasos
🔹 Probar modelos alternativos (Árboles de decisión, Random Forest, XGBoost).
🔹 Balancear clases para mejorar la tasa de recall.
🔹 Optimizar hiperparámetros para obtener mejor rendimiento.

✨ Con este análisis, se busca apoyar a la empresa en la toma de decisiones estratégicas para reducir el abandono de clientes y mejorar la retención.
Elaborado por Sandra Patricia Carrillo Velosa
