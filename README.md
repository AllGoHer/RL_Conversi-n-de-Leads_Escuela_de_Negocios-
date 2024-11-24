# Conversion-de-Leads_Escuela_de_Negocios 
Conversión de Leads de la Escuela Online de Negocios (EON) mediante Regresión Logística 

Perfil de EON
Institución de educación lider en programas de negocios online, conocida por su enfoque innovador y practico.
Problematica: Baja conversión de Leads
NECESIDAD: Urge mejorar y optimizar los proccesos de conversión de Leads para aumentar la inscripcion de estudiantes y fortalecer el crecimiento institucional. 

OBJETIVOS: 
Desarrollo de modelo: implementar un modelo de regresión logística para evaluar y puntuar cada lead.
Puntuación de Leads: asignar una puntuación a cada lead entre 0 y 100 para analizar la probabilidad de conversión.
Identificar los 'HOT LEADS'(leads de alta conversión) para optimizar las estrategias de marketing y ventas.

PROCESOS DE EJECUCIÓN
* Refinamiento de datos: limpieza de datos, manejo de valores faltantes, eliminación de duplicados.
* Transformación y selección: codificación de variables categoricas y selección meticulosa de las variables según relevancia y poder predictivo.
* Preparación para el análisis: asegurar datos para el análisis y modelado para maximizar la precisión y efeciencia del modelo futuro.
* Creación del modelo de Regresión Logistica: primero se dividiran los datos para entrenamiento y prueba para crear un modelo mas robusto,luego la construcción del modelo y finalmente la validación.
* Evalución y Testeo del Modelo: primero realizaremos unas metricas de desempeño como el análisis de precisión, sensibilidad, especifidad entre otras para evaluar la calidad del modelo; luego, realizaremos una Matriz de Confusión para entender la clasificación de los leads y la eficiencia del modelo. Y finalmente se hará una curva ROC para medir la capacidad discriminativa del modelo y optimizar el umbral de decisión.

  # Bibliotecas Utilizadas
  * Pandas
  * Numpy
  * Matplotlib
  * Seaborn
    ![image](https://github.com/user-attachments/assets/eb81b775-658f-4e01-949d-1c9d24de272d)

  * SciKit-Learn
    Desde sklearn Preprocesamiento usamos MinMaxScaler
    Desde sklearn Selección de Modelo usamos train_test_split (entrenamiento, prueba y división).
    Desde sklearn Modelo lineal importamos LogisticRegression (Regresión Logística).
    Desde sklearn metricas usamos:
    1. Matriz de confusión
       Es una herramienta que permite la visualización del desempeño de un algoritmo que se emplea en aprendizaje supervisado. Cada columna de la matriz representa el número de predicciones de cada clase, 
       mientras que cada fila representa a las instancias en la clase real. Uno de los beneficios de las matrices de confusión es que facilitan ver si el sistema está confundiendo dos clases.

       ![image](https://github.com/user-attachments/assets/6e10d2c9-4d1e-4665-aa74-91bd5d84d10e)
       
    2. AUC
       Es el acrónimo de Área Bajo la Curva (Area Under the Curve). Representa la probabilidad de que un modelo clasifique un ejemplo positivo como tal, en lugar de un ejemplo negativo, cuando se eligen al 
       azar. El valor de AUC varía entre 0 y 1, y cuanto mayor sea, mejor será el clasificador.
       
    4. Curva ROC(receiver operating characteristic)
       es una representación gráfica de la sensibilidad frente a la razón de falsas alarmas (especificidad) para un sistema clasificador binario según se varía el umbral de discriminación. Otra interpretación 
       de este gráfico es la representación de la razón o proporción de verdaderos positivos (VPR = Razón de Verdaderos Positivos) frente a la razón o proporción de falsos positivos (FPR = Razón de Falsos 
       Positivos) también según se varía el umbral de discriminación (valor a partir del cual decidimos que un caso es un positivo). Así mismo, ROC también puede significar Relative Operating Characteristic 
       (Característica Operativa Relativa) porque es una comparación de dos características operativas (VPR y FPR) según cambiamos el umbral para la decisión.
       ![image.png](attachment:aa05f83a-592a-407c-a070-0d84ca71c933.png)

  # AUTOR

📫 
   💻Autor: ALLAN GONZALES
  
   📩 allgoher007@gmail.com
  
   www.linkedin.com/in/allan-gonzales-heredia-13a557b5/
 
   https://github.com/AllGoHer/RL_Conversi-n-de-Leads_Escuela_de_Negocios    
