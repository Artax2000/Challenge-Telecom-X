# Análisis de Evasión de Clientes (Churn) en Telecomunicaciones 📉

### 📄 Descripción del Proyecto

Este repositorio contiene un análisis  del problema de la evasión de clientes (Churn) en una empresa de telecomunicaciones Telecom X. El objetivo principal es identificar y comprender los factores que influyen en la decisión de un cliente de cancelar su servicio. A través de la limpieza de datos, el análisis exploratorio de datos (EDA) y la visualización, buscamos descubrir patrones y generar insights que puedan ayudar a la empresa a desarrollar estrategias efectivas de retención de clientes. (Es parte de una actividad necesaria para avanzar en el programa ONE de Oracle, impartido por Alura Latam)

### 🛠️ Tecnologías Utilizadas

*    Python 3.x
*    Pandas: Para manipulación y análisis de datos.
*    NumPy: Para operaciones numéricas.
*    Matplotlib: Para la creación de gráficos estáticos.
*    Seaborn: Para visualizaciones estadísticas más atractivas.
*    Jupyter Notebook / Google Colab: Entorno de desarrollo interactivo.

### 📊 Estructura del Repositorio

*    notebooks/:
        TelecomX_LATAM.ipynb: El cuaderno principal de Jupyter/Colab que contiene todo el código de limpieza, EDA y visualizaciones.
    data/:
        TelecomX_Data.json: El dataset original utilizado para el análisis.
    README.md: Este archivo.

### 🚀 Cómo Ejecutar el Análisis

*   Google Colab: Sube el archivo TelecomX_LATAM.ipynb a tu Google Drive y ábrelo desde allí. Asegúrate de que el archivo de datos TelecomX_Data.json esté accesible (ej., subido también a Colab o desde un enlace directo).

*   Ejecuta las Celdas: Sigue el cuaderno celda por celda para ver el proceso de limpieza, el EDA y los resultados.

### 💡 Hallazgos Principales (Insights Clave)

Los análisis revelaron varios patrones importantes en la evasión de clientes:

*  Tasa de Evasión: Se observó una tasa de evasión general del 26.6%.

*  Impacto del Tipo de Contrato: Los clientes con contratos de mes a mes muestran una propensión significativamente mayor a la evasión en comparación con aquellos con contratos anuales o bianuales.

*  Método de Pago: El cheque electrónico se identifica como el método de pago más asociado con la evasión.

*  Gasto Total (cargo_total): Los clientes que cancelan el servicio tienen un gasto total acumulado significativamente menor ($1531.80 de media) en comparación con los que permanecen ($2555.34 de media). Esto sugiere que clientes con menor lealtad o menos servicios son más propensos a irse.

*  Cuentas Diarias (cuentas_diarias): Curiosamente, los clientes que cancelan tienen un promedio ligeramente mayor de 'cuentas diarias' ($2.48 de media) que los que permanecen ($2.04 de media), con una correlación positiva débil (0.193). Esto podría indicar una posible insatisfacción entre usuarios más intensivos.

*  Cantidad de Servicios Contratados (num_servicios): Existe una correlación negativa muy débil (-0.067), indicando que los clientes con un menor número de servicios contratados son marginalmente más propensos a la evasión. Esto sugiere una menor "adherencia" a la empresa.

*  Demografía:  No se encontró una correlación fuerte entre el género o la edad (>65 años) y la propensión a la evasión dentro de los clientes que cancelaron.

### 🚀 Recomendaciones Estratégicas

Basado en los hallazgos, se proponen las siguientes recomendaciones para reducir la evasión:

*    Incentivar Contratos a Largo Plazo: Ofrecer descuentos o beneficios exclusivos para fomentar la adopción de contratos de uno o dos años.

*    Optimizar Experiencia de Pago Electrónico: Investigar las causas de la alta evasión en usuarios de cheque electrónico y ofrecer alternativas más cómodas o programas de fidelización específicos.

*    Monitoreo y Proactividad con Clientes de Bajo Gasto/Antigüedad: Identificar a clientes con bajo gasto total y/o baja antigüedad para ofrecer "check-ins" proactivos, promociones personalizadas o mejoras de servicio.

*    Atención Especial a Clientes de Alto Uso (Cuentas Diarias): Investigar las razones detrás de la evasión de clientes con alto uso de 'cuentas diarias' para asegurar que sus necesidades de rendimiento y soporte estén siendo satisfechas.

*    Estrategias de Venta Cruzada/Up-selling: Dirigir esfuerzos para que los clientes con pocos servicios contraten más, aumentando así su "adherencia" a la empresa.

### 🤝 Contribuciones

Si tienes sugerencias o mejoras, ¡son bienvenidas! Por favor, abre un "issue" o envía un "pull request".

