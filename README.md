# 📊 Análisis de Evasión de Clientes (Churn) - Telecom X

Este proyecto fue desarrollado como parte del programa de formación en Data Science de Alura Latam. El objetivo es analizar el comportamiento de los clientes de Telecom X para identificar factores que influyen en la evasión de clientes (Churn).

---

## 🎯 Objetivo del proyecto

Analizar los datos de clientes de Telecom X para encontrar patrones que expliquen por qué algunos clientes cancelan el servicio y proponer recomendaciones que ayuden a reducir la evasión.

---

## 📂 Dataset

El conjunto de datos contiene información sobre:

- Datos demográficos de los clientes
- Servicios contratados
- Tipo de contrato
- Método de pago
- Tiempo de permanencia
- Facturación mensual y total
- Estado de evasión (Churn)

---

## 🧹 Limpieza y preparación de datos

Durante esta etapa se realizaron los siguientes procesos:

- Carga de datos desde una API en formato JSON
- Conversión a DataFrame usando Pandas
- Revisión de tipos de datos
- Identificación de valores nulos e inconsistencias
- Transformación de la variable **Churn** a valores binarios (0 y 1)
- Creación de la columna **Cuentas_Diarias**
- Conversión de variables numéricas para el análisis

---

## 📈 Análisis Exploratorio de Datos

Se realizaron diferentes análisis para entender el comportamiento de los clientes:

### Distribución de evasión
Se analizó la proporción de clientes que permanecen en la empresa frente a los que cancelan el servicio.

### Variables categóricas analizadas

- Género
- Tipo de contrato
- Método de pago
- Servicio de internet
- Soporte técnico
- Clientes con pareja o dependientes

Hallazgos importantes:

- Los contratos **Month-to-month** presentan mayor evasión.
- El método de pago **Electronic check** tiene mayor cantidad de cancelaciones.
- Los clientes con **Fiber Optic** presentan más churn.
- Los clientes sin **Tech Support** tienen mayor probabilidad de irse.

### Variables numéricas analizadas

- Tenure (tiempo en la empresa)
- Charges.Monthly
- Charges.Total
- Cuentas_Diarias

Se observó que:

- Los clientes que cancelan suelen tener **menos tiempo en la empresa**.
- Existe relación entre el costo del servicio y la evasión.

---

## 🔍 Conclusiones

El análisis permitió identificar factores clave asociados con la evasión de clientes:

- Clientes nuevos tienen mayor probabilidad de cancelar.
- Contratos mensuales presentan mayor riesgo de churn.
- La falta de soporte técnico influye en la cancelación.
- Algunos métodos de pago están más asociados con la evasión.

---

## 💡 Recomendaciones

Para reducir la evasión de clientes se recomienda:

- Incentivar contratos de largo plazo.
- Mejorar el servicio de soporte técnico.
- Crear estrategias de fidelización para clientes nuevos.
- Analizar posibles mejoras en el servicio de fibra óptica.
- Revisar la experiencia de usuarios con ciertos métodos de pago.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

---

## 📌 Autor

Proyecto desarrollado por **Yeicob David Rodriguez** como parte del programa de formación en Data Science.
