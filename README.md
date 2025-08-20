# Predicción de Cancelación de Clientes - Telecom X Parte 2
El objetivo fue desarrollar un sistema para predecir qué clientes tienen mayor probabilidad de cancelar sus servicios :chart_with_upwards_trend:, facilitando estrategias de retención :shield:.

- **Limpieza y Preprocesamiento de Datos**: estandarización y conversión a formatos numéricos.  
- **Balanceo de Clases**: oversampling para corregir desbalance natural.  
- **Modelado y Evaluación**: entrenamiento de Regresión Logística y Random Forest; evaluación mediante Precisión, Recall y F1-Score.  
- **Análisis de Importancia**: identificación de variables más influyentes .


## Factores Clave en la Cancelación de Clientes

1. **Tipo de Contrato :key:**  
   - Contract_Month-to-month --> mayor riesgo de cancelación.  
   - Contratos a 1 o 2 años --> mayor retención.

2. **Antigüedad del Cliente :hourglass_flowing_sand:**  
   - Mayor tenure --> menor probabilidad de churn.  
   - Clientes nuevos son los más propensos a cancelar.

3. **Costo y Configuración del Servicio :money_with_wings:**  
   - Fibra óptica ? mayor cancelación.  
   - Método de pago con cheque electrónico --> riesgo elevado.


## Modelos Utilizados

- **Regresión Logística** :straight_ruler: interpretable, requiere normalización, alto Recall para detectar clientes en riesgo.  
- **Árbol de Decisión / Random Forest** :deciduous_tree: captura relaciones no lineales, reglas claras, buen rendimiento general.


## Conclusión Final :trophy:

La cancelación de clientes no es aleatoria, sino predecible. Comprender los factores críticos y aplicar modelos predictivos permite:

- Identificar clientes en riesgo tempranamente.  
- Implementar estrategias de retención efectivas.  
- Reducir la tasa de churn y aumentar el valor de vida del cliente.  

