# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

---

## 🧠 Introducción

Este proyecto analiza el fenómeno de **evasión de clientes (churn)** en Telecom X, con el objetivo de identificar patrones y factores asociados a la cancelación del servicio.

La evasión de clientes representa un problema relevante para el negocio, ya que impacta directamente en la estabilidad y los ingresos. A través del análisis de datos, se busca generar información que sirva como base para futuras estrategias de retención y modelos predictivos.

El trabajo forma parte del **Challenge Telecom X del programa de formación de Alura** y tiene **fines educativos y analíticos**.

---

## 🎯 Objetivos del análisis

El análisis busca evaluar la distribución del churn entre los clientes, identificar variables categóricas asociadas con la evasión, comparar variables numéricas entre quienes cancelan y quienes permanecen, explorar relaciones mediante análisis de correlación y generar insights que apoyen la toma de decisiones estratégicas. 📊

---

## 🧹 Limpieza y preparación de datos

Durante la preparación de los datos se realizó la carga desde la API en formato JSON, su conversión a un DataFrame para facilitar el análisis, la revisión y tratamiento de valores inconsistentes o faltantes, la conversión de variables numéricas a su tipo correcto, la estandarización de variables binarias (Yes/No) y la creación de variables derivadas como Cuentas_Diarias.

---

## 📊 Análisis Exploratorio de Datos (EDA)

### 🔹 Distribución de evasión
- Se analizó la proporción de clientes que cancelaron el servicio frente a aquellos que permanecieron activos.

### 🔹 Variables categóricas
- Se evaluó la relación del churn con variables como tipo de contrato, género y método de pago.
- Se observó una mayor tasa de evasión en clientes con contratos mensuales y en ciertos métodos de pago.

### 🔹 Variables numéricas
- Se compararon variables como **antigüedad, cargos mensuales, total gastado y cuentas diarias** mediante **boxplots** para observar su distribución, mediana y valores atípicos.
- Los clientes que cancelan suelen tener **menor antigüedad**.
- Los clientes con churn presentan **cargos mensuales más altos en promedio**.
- El **total gastado** se encuentra fuertemente relacionado con la antigüedad del cliente.

### 🔹 Análisis de correlación
- Se construyó una **matriz de correlación** para identificar relaciones entre variables numéricas.
- Se encontró una **relación inversa entre antigüedad y churn**.
- Los **cargos mensuales y diarios** muestran asociación positiva con la evasión.
- El **total gastado** presenta una fuerte correlación con la antigüedad del cliente.

---

## 📌 Conclusiones e insights

El análisis revela que el churn es un desafío significativo, impulsado principalmente por la **antigüedad del cliente**, el **tipo de contrato** y la **adopción de servicios de valor agregado**. Para combatir esto, se propone una estrategia multifacética que abarca la retención proactiva de clientes nuevos, la incentivación de contratos y pagos automáticos a largo plazo, y la promoción de servicios de seguridad y soporte.

Como próximos pasos, se recomienda la **construcción de un modelo predictivo de churn** a corto plazo, la implementación de un **sistema de scoring de riesgo** y un **dashboard de monitoreo** a mediano plazo, y la realización de **A/B testing de estrategias de retención** y **análisis de cohortes** a largo plazo para una mejora continua y basada en datos.

---

## 💡 Recomendaciones

1.  **Programa de Retención para Clientes Nuevos:** Implementar un programa de onboarding robusto (primeros 3-6 meses) con seguimiento proactivo, descuentos introductorios y educación sobre servicios para reducir el churn en este segmento de alto riesgo.
2.  **Incentivos para Contratos de Largo Plazo:** Ofrecer beneficios atractivos (descuentos, servicios premium, garantía de precio) para migrar clientes de contratos mensuales a anuales o bianuales.
3.  **Promoción de Servicios de Valor Agregado:** Fomentar la adopción de servicios como OnlineSecurity, OnlineBackup y TechSupport a través de paquetes con descuento, pruebas gratuitas y demostraciones de su valor.
4.  **Optimización de Métodos de Pago:** Incentivar los pagos automáticos con descuentos y simplificar el proceso de configuración, reduciendo el uso del 'Electronic check'.
5.  **Segmentación y Personalización:** Crear ofertas y estrategias de intervención personalizadas para segmentos de alto riesgo, como adultos mayores sin soporte, clientes con contratos 'Month-to-month' y cargos altos, y nuevos clientes de Fibra Óptica.
6.  **Revisión de Precios de Fibra Óptica:** Analizar la competitividad del precio y el valor percibido de la Fibra Óptica para reducir el churn en este segmento.
7.  **Monitoreo y Programas de Lealtad:** Implementar un sistema de monitoreo preventivo, especialmente para clientes con gasto diario superior a $2.50. Ofrecer paquetes o 'bundles' para aumentar la cantidad de servicios contratados, lo que podría reducir el churn a la mitad.

---

## 🛠️ Tecnologías utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---
