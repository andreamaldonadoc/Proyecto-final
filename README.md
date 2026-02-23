# 📡 Proyecto Interconnect: Predicción de Cancelación de Clientes

## Contexto
Interconnect, un operador de telecomunicaciones, busca reducir su tasa de cancelación de clientes.  
El objetivo es construir un modelo de predicción que identifique usuarios con alta probabilidad de cancelar su contrato, para ofrecerles códigos promocionales y planes especiales que mejoren su retención.

Este proyecto forma parte de mi portfolio como analista de datos, demostrando habilidades técnicas en **análisis exploratorio, modelado predictivo y comunicación de resultados**.


## Objetivos del Proyecto
- Analizar datos de contratos, servicios y características personales de clientes.
- Identificar patrones asociados a la cancelación de servicios.
- Construir un modelo de machine learning para predecir la tasa de cancelación.
- Proponer estrategias de retención basadas en los hallazgos.


## Servicios de Interconnect
Interconnect ofrece:
- **Telefonía fija** con múltiples líneas simultáneas.
- **Internet** vía DSL o fibra óptica.
- Servicios adicionales:
  - Seguridad en Internet (*ProtecciónDeDispositivo*, *SeguridadEnLínea*).
  - Soporte técnico (*SoporteTécnico*).
  - Backup y almacenamiento en la nube (*BackupOnline*).
  - Streaming de TV y películas (*StreamingTV*, *StreamingPelículas*).

Los clientes pueden elegir contratos de 1 o 2 años, o pagos mensuales, con múltiples métodos de pago y facturación electrónica.


## Descripción de los Datos
Los datos provienen de diferentes fuentes y están organizados en archivos CSV:

- `contract.csv` — información del contrato.  
- `personal.csv` — datos personales del cliente.  
- `internet.csv` — servicios de Internet contratados.  
- `phone.csv` — servicios telefónicos contratados.  

Cada archivo contiene la columna `customerID` como identificador único.  
La información de contratos es válida a partir del **1 de febrero de 2020**.


## Metodología
1. **Exploración de datos (EDA)**: limpieza, análisis de valores nulos y distribución de variables.  
2. **Feature engineering**: creación de variables relevantes (ej. duración del contrato, tipo de servicio).  
3. **Modelado predictivo**: entrenamiento de modelos de clasificación (Logistic Regression, Random Forest, XGBoost).  
4. **Evaluación**: métricas como *accuracy*, *precision*, *recall* y *ROC-AUC*.  
5. **Interpretación de resultados**: identificación de factores clave en la cancelación.  


## Resultados Esperados
- Un modelo capaz de anticipar cancelaciones con alta precisión.  
- Recomendaciones para el equipo de marketing sobre clientes en riesgo.  
- Estrategias de retención basadas en datos (ej. promociones específicas según tipo de contrato o servicio).  


## Contribución y Trabajo en Equipo
Este proyecto refleja mi capacidad para:
- **Colaborar con equipos multidisciplinarios** (marketing, soporte técnico, IT).  
- **Comunicar hallazgos de manera clara y efectiva** a perfiles no técnicos.  
- **Aplicar buenas prácticas de ciencia de datos** en proyectos reales.  


## Tecnologías Utilizadas
- Python (pandas, scikit-learn, matplotlib, seaborn, XGBoost).  
- Jupyter Notebook.  
- Git/GitHub para control de versiones.  
- Visual Studio Code como entorno de desarrollo.  

