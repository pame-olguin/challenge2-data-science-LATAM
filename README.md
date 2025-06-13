# 📊 **Análisis de Evasión de Clientes (Churn) - TelecomX**  

## 📌 **Descripción del Proyecto**  
Este proyecto analiza la **evasión de clientes (Churn)** en una empresa de telecomunicaciones. Utilizamos datos de **TelecomX** para identificar patrones que afectan la cancelación del servicio y ofrecer estrategias para mejorar la **retención de clientes**.  

Se desarrolla un análisis exploratorio de datos mediante **visualizaciones, correlaciones y estadísticas**, complementado con recomendaciones estratégicas.  

---

## 📂 **Estructura del Proyecto**
 
📦 challenge2-data-science-LATAM/  
├── 📄 README.md                         # Documentación del proyecto  
├── 📁 data/                             # Datos utilizados en el análisis  
│   └── TelecomX_Data.json              # Datos en formato JSON  
├── 📁 notebooks/                        # Análisis y exploración de datos  
│   ├── TelecomX_LATAM.ipynb            # Notebook con el análisis principal  
│   └── challenge2_data_science_LATAM.ipynb  # Segundo desafío  
├── 📁 docs/                             # Documentación y diccionario de datos  
│   └── TelecomX_diccionario.md         # Diccionario de variables  

---

## 🔍 **Objetivos del Análisis**
✅ **Analizar las principales razones de cancelación de clientes.**  
✅ **Evaluar cómo afectan el tipo de contrato, método de pago y costos en la evasión.**  
✅ **Visualizar patrones en los datos con gráficos y estadísticas.**  
✅ **Proponer estrategias basadas en insights clave.**  

---

 ## 🔍 **Limpieza y tratamiento de los datos**
Antes de realizar el análisis, se realizaron las siguientes acciones para preparar los datos correctamente:

✅ Importación de datos desde una API en formato Json.

✅Conversión de datos y normalización para transformar información estructurada en columnas separadas.

✅Manejo de valores faltantes en columnas "Cancelaciones" reemplazando '' por 'no se sabe ' y en columna "Cargos Totales" reemplazando los NaN por '0'.

✅Estandarización del texto de mayúsculas a minúsculas para evitar duplicados en las categorías.

✅Conversión de variables binarias de "yes" ,"no" "no se sabe" a "0","1" y "-1" respectivamente para facilitar análisis numéricos.

✅Renombramiento de columnas de inglés a español para mejorar la legibilidad.

---
## 🚀 **Tecnologías Utilizadas**
- 🐍 **Python 3.8+**
- 📊 **Pandas**, **NumPy** (manipulación de datos)
- 📉 **Matplotlib**, **Seaborn** (visualización)
- 🔍 **Scikit-Learn** (para modelos predictivos, si aplica)

---

## 📊 **Hallazgos Clave**

- 🔹 **Clientes con contratos mensuales** presentan la mayor tasa de cancelación (**42.7%**).
- 🔹 **Clientes nuevos** tienen más riesgo de cancelar, con una antigüedad media de **18 meses**.
- 🔹 **Clientes con cargos mensuales altos** tienden a cancelar más.
- 🔹 **Clientes con facturación electrónica** cancelan más que los que usan facturación tradicional.
- 🔹 **Servicios adicionales** como seguridad en línea y soporte técnico ayudan a reducir la cancelación.

---

## 🔍 **Conclusiones e Insights**

✅ **Los clientes nuevos son más propensos a cancelar**, lo que destaca la importancia de estrategias de retención en los primeros meses.

✅ **Los contratos mensuales presentan una cancelación elevada**, lo que sugiere que los planes a largo plazo pueden mejorar la retención.

✅ **Los clientes con cargos mensuales altos tienden a cancelar más**, lo que puede indicar que el costo percibido no se alinea con el valor del servicio.

✅ **Los clientes que tienen soporte técnico y seguridad en línea tienen menor cancelación**, lo que resalta la importancia de ofrecer servicios complementarios.

✅ **La facturación sin papel tiene una tasa de cancelación más alta**, lo que podría estar relacionado con la percepción del servicio y la comunicación.

---

## 🧭 **Recomendaciones Estratégicas**

✅ **Retención en los primeros meses** ➡ Ofrecer descuentos, soporte proactivo y programas de fidelización.

✅ **Optimizar planes de contrato** ➡ Incentivar a clientes mensuales a migrar a planes anuales con beneficios exclusivos.

✅ **Analizar métodos de pago** ➡ Evaluar por qué la facturación electrónica tiene más cancelación.

✅ **Fortalecer la comunicación** ➡ Mejorar la percepción de clientes con facturación sin papel.

✅ **Promover servicios adicionales** ➡ Fomentar el uso de seguridad en línea y soporte técnico para reducir la evasión.
