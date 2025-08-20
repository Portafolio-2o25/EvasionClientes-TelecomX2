# Proyecto de Predicci�n de Cancelaci�n de Clientes - Telecom X Parte 2

**Resumen del Proyecto**  
El objetivo fue desarrollar un sistema para predecir qu� clientes tienen mayor probabilidad de cancelar sus servicios (`:chart_with_upwards_trend:`), facilitando estrategias de retenci�n (`:shield:`). El flujo incluy�:

- **Limpieza y Preprocesamiento de Datos**: estandarizaci�n y conversi�n a formatos num�ricos (`:wastebasket:`).  
- **Balanceo de Clases**: oversampling para corregir desbalance natural (`:balance_scale:`).  
- **Modelado y Evaluaci�n**: entrenamiento de Regresi�n Log�stica y Random Forest; evaluaci�n mediante Precisi�n, Recall y F1-Score (`:bar_chart:`).  
- **An�lisis de Importancia**: identificaci�n de variables m�s influyentes (`:mag:`).


## Factores Clave en la Cancelaci�n de Clientes

1. **Tipo de Contrato (`:key:`)**  
   - Mes a mes (`Contract_Month-to-month`) ? mayor riesgo de cancelaci�n (`:warning:`).  
   - Contratos a 1 o 2 a�os ? mayor retenci�n (`:lock:`).

2. **Antig�edad del Cliente (`:hourglass_flowing_sand:`)**  
   - Mayor tenure ? menor probabilidad de churn (`:arrow_down_small:`).  
   - Clientes nuevos son los m�s propensos a cancelar (`:exclamation:`).

3. **Costo y Configuraci�n del Servicio (`:money_with_wings:`)**  
   - Fibra �ptica ? mayor cancelaci�n (`:electric_plug:`).  
   - M�todo de pago con cheque electr�nico ? riesgo elevado (`:credit_card:`).


## Modelos Utilizados

- **Regresi�n Log�stica** (`:straight_ruler:`): interpretable, requiere normalizaci�n, alto Recall para detectar clientes en riesgo.  
- **�rbol de Decisi�n / Random Forest** (`:deciduous_tree:`): captura relaciones no lineales, reglas claras, buen rendimiento general.


## Conclusi�n Final (`:trophy:`)

La cancelaci�n de clientes no es aleatoria, sino predecible. Comprender los factores cr�ticos y aplicar modelos predictivos permite:

- Identificar clientes en riesgo tempranamente (`:mag_right:`).  
- Implementar estrategias de retenci�n efectivas (`:shield:`).  
- Reducir la tasa de churn y aumentar el valor de vida del cliente (`:moneybag:`).  

