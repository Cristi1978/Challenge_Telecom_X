# Challenge_Telecom_X.

🔍**Análisis de Cancelación de Clientes en Telecomunicaciones**.

Telecom X es una empresa de telecomunicaciones que está enfrentando un alto índice de evasión de clientes (churn). Aún no se han identificado las causas principales detrás de esta evasión, por lo que este proyecto busca analizar los datos disponibles y brindar información clave para ayudar a resolver este problema.

📋**Descripción del Proyecto**.

  Este proyecto realiza un análisis exploratorio exhaustivo de un conjunto de datos de clientes de telecomunicaciones para identificar los factores clave que        influyen en la cancelación del servicio (churn). El objetivo es comprender mejor el comportamiento del cliente y proporcionar información valiosa para             desarrollar estrategias de retención efectivas.

📁**Conjunto de Datos**.

  El análisis se basa en el conjunto de datos "TelecomX_Data.json", proporcionado por Alura LATAM. Este dataset contiene información detallada sobre cada cliente,   incluyendo:

*   Datos demográficos (género, edad, estado civil, dependientes).
*   Servicios contratados (servicio telefónico, múltiples líneas, servicio de internet, seguridad en línea, etc.)
*   Información de contrato y pago (tipo de contrato, método de pago, cargos mensuales y totales).
*   Estado de cancelación (si el cliente ha cancelado el servicio).

  🔄**Objetivos del Análisis**.
  
*   Explorar y comprender la estructura y el contenido del conjunto de datos.
*   Realizar limpieza y transformación de datos, incluyendo la normalización de estructuras anidadas y el manejo de valores faltantes o inconsistentes.
*   Identificar y analizar la proporción general de cancelación.
*   Investigar la relación entre diversas características del cliente (demográficas, servicios, contrato, pago) y la probabilidad de cancelación.
*   Presentar los hallazgos clave de manera clara y visual.

  🛠️ **Metodología y Herramientas**
  
  El análisis se llevó a cabo utilizando Python y las siguientes bibliotecas principales:

*   `pandas` para manipulación y análisis de datos.
*   `numpy` para operaciones numéricas.
*   `matplotlib` y `seaborn` `plotly.express` para visualizaciones
*  `requests` para la extracción de datos desde la URL proporcionada.

📦 **Guía de Instalación y Ejecución**

 * **Entorno**: Este notebook está diseñado para ejecutarse en Google Colab.

 * **Librerías**: Las librerías principales (pandas, matplotlib, seaborn) suelen estar preinstaladas en Colab. No se requieren instalaciones adicionales.

 * **Abrir Notebook**: Sube o abre el archivo TelecomX_LATAM.ipynb en Google Colab.

 * **Ejecutar Celdas**: Ejecuta las celdas de código en orden secuencial (de arriba abajo, usando Shift+Enter o el botón de Play). Es crucial ejecutar las celdas      de las secciones Extracción y Transformación para que  el DataFrame df_final esté definido y listo para los análisis posteriores.


  📊**Caracteristicas técnicas del Análisis:**
   
 1.  **Extracción de Datos:** Carga del archivo JSON desde la URL.

 2.  **Transformación de Datos:** Normalización de columnas anidadas, limpieza de datos (manejo de valores vacíos en 'cancelacion' y 'ingreso_total_cliente'),          conversión de tipos de datos, renombrado de columnas y  creación de nuevas características ('cuentas_diarias', 'tiempo_de_contrato').

 3.  **Análisis Exploratorio:** Cálculo de estadísticas descriptivas, verificación de valores únicos, duplicados y nulos. Análisis de la proporción de cancelación      por diferentes variables categóricas (género, tipo de contrato, método de pago, servicio de internet, etc.) mediante tablas y gráficos.
  
 4.  **Visualización:** Creación de gráficos de barras apiladas y otros gráficos relevantes para ilustrar los hallazgos clave.
    

   📌  **Hallazgos Clave**.

 *  Los principales hallazgos del análisis incluyen:

 * Proporción general de clientes que cancelaron: 26.5%.
  
 * Factores con mayor influencia en la cancelación:
  
   * **Tipo de Contrato** - Clientes con contratos mes a mes tienen mayor tasa de cancelación.
    
   * **Método de Pago** - El pago electrónico se asocia con mayor cancelación. 
  
   * **Servicio de Internet** - Fibra óptica con mayor tasa de cancelación.
  
   * **Demografía** - Adultos mayores, sin pareja/dependientes, mayor cancelación.
  
   * **Servicios Adicionales** - La falta de ciertos servicios incrementa la cancelación.
  

 📦 **Guía de Instalación y Ejecución**

1.  Asegúrate de tener Python instalado y las bibliotecas mencionadas (`pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly-express`, `requests`). Puedes               instalarlas usando pip:
    ```bash
    pip install pandas numpy matplotlib seaborn plotly-express requests
    ```
2.  Descarga el archivo del notebook de Colab (`.ipynb`) desde este repositorio.
3.  Abre el notebook en Google Colab o en un entorno Jupyter local.
4.  Ejecuta todas las celdas del notebook en orden para cargar los datos, realizar la limpieza, transformación y análisis exploratorio.
5.  Observa las salidas de cada celda: tablas de datos, gráficos y textos de análisis.
6.  Con las visualizaciones puedes identificar patrones de comportamiento de los clientes.
7.  Lee el Informe Final para entender Conclusiones y Recomendaciones propuestas.


  💻 **Conclusiones y Recomendaciones**
   
  En resumen, este análisis identificó que la tasa general de cancelación es del 26.5%, lo que subraya la importancia de abordar este problema. Los factores que     más influyen en que un cliente abandone la empresa   son el tipo de contrato (los de mes a mes cancelan más), el método de pago (especialmente el electrónico),    el servicio de internet (la fibra óptica presenta una tasa más alta), ciertas características demográficas (adultos mayores, sin pareja/dependientes) y la falta   de suscripción a servicios adicionales, particularmente los de seguridad y soporte técnico. Para reducir esta tasa, se recomienda enfocar los esfuerzos en         incentivar contratos a largo plazo, mejorar la experiencia con el pago electrónico, abordar posibles problemas con el servicio de fibra óptica, implementar        programas de retención dirigidos a segmentos de alto riesgo y promover activamente los servicios adicionales.
  


 👥 **Autor**


**Cristina Valenzuela**

**Curso: Formación en Data Science**

**Programa ONE Alura Latam**




