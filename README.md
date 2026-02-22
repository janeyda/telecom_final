# telecom_final
📊 Telecom X – Predicción de Cancelación (Churn)

📣 Objetivo
Predecir qué clientes tienen mayor probabilidad de cancelar sus servicios (churn) para implementar estrategias de retención proactivas.

🧰 Herramientas
Python, Pandas, NumPy
Scikit-learn, Imbalanced-learn (SMOTE)
Matplotlib, Seaborn

🔹 Preprocesamiento
Se codificaron variables categóricas (One-Hot Encoding).
Se eliminó información irrelevante (customerID, Churn).
Se balancearon las clases con SMOTE.
Se normalizaron variables para modelos sensibles a la escala (KNN, Regresión).

🔹 Modelos Evaluados

 Dummy Classifier  
 Árbol de Decisión 
 
 KNN               
 Random Forest

🔹 Factores Clave de Cancelación
tenure (antigüedad) – Clientes recientes son más propensos a cancelar.
Charges.Monthly (costo mensual) – Tarifas altas aumentan churn.
Contract (tipo de contrato) – Mes a mes → más cancelaciones.
TechSupport – Ausencia de soporte aumenta la probabilidad de churn.
Otros factores: servicios adicionales (OnlineSecurity, OnlineBackup), presencia de familia (Partner, Dependents).

🔹 Estrategias de Retención
Fidelización temprana: descuentos y promociones en los primeros meses.
Mejorar soporte técnico y servicios adicionales.
Incentivar contratos a largo plazo con beneficios y bonificaciones.
Identificar clientes de riesgo mediante Random Forest y contacto proactivo.
Ajuste de precios y planes flexibles según perfil del cliente.
📌 Conclusión
Random Forest permite identificar clientes propensos a cancelar de manera confiable.
La combinación de análisis de datos y estrategias de retención puede reducir significativamente la tasa de churn y aumentar la lealtad del cliente.

📂 Enlaces
Notebook del proyecto: final_de_TelecomX_LATAM_2.ipynb
Dataset limpio: empresa_limpia.csv
