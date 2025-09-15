# Predicción de Churn de Clientes

📊 **Objetivo**  
Predecir la probabilidad de que un cliente abandone un servicio (churn), con el fin de anticipar pérdidas y diseñar estrategias de retención más efectivas.

🗂️ **Dataset**  
- [Telco Customer Churn (Kaggle)](https://www.kaggle.com/blastchar/telco-customer-churn)  
- 7,043 registros con variables de uso, tipo de contrato, demografía y servicios contratados.

🛠️ **Técnicas y Herramientas**  
- Lenguajes: Python (Pandas, Scikit-learn, Matplotlib, Seaborn).  
- Modelos: Regresión Logística, Random Forest, XGBoost.  
- Evaluación: ROC-AUC, Matriz de Confusión, Precision/Recall.  

📈 **Resultados**  
- El modelo XGBoost alcanzó un ROC-AUC de **0.87**.  
- Variables más influyentes: tipo de contrato, tenencia, cargos mensuales.  

💡 **Conclusiones de negocio**  
Con este modelo se pueden identificar clientes con alto riesgo de churn y crear campañas personalizadas, lo que potencialmente reduciría en un **15–20% la pérdida de clientes**.  
