# Proyecto de Predicción de Cancelación de Clientes - Telecom X Parte 2

**Resumen del Proyecto**  
El objetivo fue desarrollar un sistema para predecir qué clientes tienen mayor probabilidad de cancelar sus servicios (`:chart_with_upwards_trend:`), facilitando estrategias de retención (`:shield:`). El flujo incluyó:

- **Limpieza y Preprocesamiento de Datos**: estandarización y conversión a formatos numéricos (`:wastebasket:`).  
- **Balanceo de Clases**: oversampling para corregir desbalance natural (`:balance_scale:`).  
- **Modelado y Evaluación**: entrenamiento de Regresión Logística y Random Forest; evaluación mediante Precisión, Recall y F1-Score (`:bar_chart:`).  
- **Análisis de Importancia**: identificación de variables más influyentes (`:mag:`).


## Factores Clave en la Cancelación de Clientes

1. **Tipo de Contrato (`:key:`)**  
   - Mes a mes (`Contract_Month-to-month`) ? mayor riesgo de cancelación (`:warning:`).  
   - Contratos a 1 o 2 años ? mayor retención (`:lock:`).

2. **Antigüedad del Cliente (`:hourglass_flowing_sand:`)**  
   - Mayor tenure ? menor probabilidad de churn (`:arrow_down_small:`).  
   - Clientes nuevos son los más propensos a cancelar (`:exclamation:`).

3. **Costo y Configuración del Servicio (`:money_with_wings:`)**  
   - Fibra óptica ? mayor cancelación (`:electric_plug:`).  
   - Método de pago con cheque electrónico ? riesgo elevado (`:credit_card:`).


## Modelos Utilizados

- **Regresión Logística** (`:straight_ruler:`): interpretable, requiere normalización, alto Recall para detectar clientes en riesgo.  
- **Árbol de Decisión / Random Forest** (`:deciduous_tree:`): captura relaciones no lineales, reglas claras, buen rendimiento general.


## Conclusión Final (`:trophy:`)

La cancelación de clientes no es aleatoria, sino predecible. Comprender los factores críticos y aplicar modelos predictivos permite:

- Identificar clientes en riesgo tempranamente (`:mag_right:`).  
- Implementar estrategias de retención efectivas (`:shield:`).  
- Reducir la tasa de churn y aumentar el valor de vida del cliente (`:moneybag:`).  

