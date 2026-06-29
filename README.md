# Introducción a Machine Learning para Ingenieros e Ingenieras del Área Química

Repositorio del curso **Machine Learning introductorio para estudiantes de licenciatura del área química**, diseñado como una experiencia formativa basada en casos aplicados a problemas de ingeniería química, ingeniería ambiental, materiales y procesos.

El curso utiliza la metodología de **Aprendizaje Basado en Casos**, por lo que cada sesión parte de un problema contextualizado y se desarrolla mediante notebooks en **Google Colab**, integrando análisis de datos, construcción de modelos, evaluación de resultados e interpretación desde una perspectiva ingenieril.

Este material también forma parte de una propuesta de **investigación educativa**, orientada a analizar el aprendizaje, la percepción estudiantil y el desarrollo de competencias relacionadas con el uso de Machine Learning, Python y herramientas computacionales en la formación de estudiantes del área química.

---

## Objetivo del curso

Desarrollar en estudiantes de licenciatura del área química una comprensión introductoria, aplicada y crítica de los fundamentos del **Machine Learning**, mediante la metodología de **Aprendizaje Basado en Casos**, para analizar datos, construir modelos predictivos y de agrupamiento, evaluar su desempeño e interpretar sus resultados en problemas relacionados con propiedades fisicoquímicas, calidad de agua, diseño de materiales y monitoreo ambiental, utilizando herramientas computacionales accesibles como **Google Colab**, con énfasis en la toma de decisiones ingenieriles, el uso responsable de la inteligencia artificial y la generación de evidencias para investigación educativa.

---

## Público objetivo

Este curso está dirigido a estudiantes de licenciatura de programas relacionados con:

* Ingeniería Química
* Ingeniería Ambiental
* Ingeniería en Alimentos
* Ingeniería en Materiales
* Ingeniería en Biotecnología
* Áreas afines a procesos químicos, ambientales o industriales

No se requiere experiencia avanzada en programación o Machine Learning. El curso está diseñado como una introducción aplicada y guiada.

---

## Metodología

El curso se desarrolla mediante **Aprendizaje Basado en Casos**. Cada sesión incluye:

* contexto del problema;
* pregunta detonadora;
* conceptos fundamentales;
* datos reales o simulados;
* desarrollo guiado en Python;
* construcción de modelos de Machine Learning;
* evaluación mediante métricas;
* interpretación de resultados;
* reflexión sobre alcances, limitaciones e implicaciones éticas.

Las actividades se realizan principalmente en **Google Colab**, por lo que no es necesario instalar Python localmente.

---

## Temario del curso

| Sesión | Tema                                        | Enfoque principal                                                         |
| ------ | ------------------------------------------- | ------------------------------------------------------------------------- |
| 1      | Del problema químico al modelo              | Identificación de oportunidades de Machine Learning en ingeniería química |
| 2      | Predicción de solubilidad acuosa            | Regresión supervisada con SMILES, RDKit y descriptores moleculares        |
| 3      | Clasificación de calidad de agua            | Clasificación supervisada para apoyar decisiones ambientales              |
| 4      | Clustering para diseño de nuevos materiales | Agrupamiento de materiales reales por similitud química y electrónica     |
| 5      | TinyML con Arduino Uno                      | Introducción al despliegue de modelos usando emlearn                      |

---

## Contenido del repositorio

```text
.
├── 01_introduccion_ml_ingenieria_quimica.ipynb
├── 02_regresion_solubilidad_smiles_rdkit.ipynb
├── 03_clasificacion_calidad_agua_ml.ipynb
├── 04_clustering_simple_materiales_reales.ipynb
├── 05_tinyml_emlearn_arduino_uno.ipynb
└── README.md
```

---

## Descripción de las sesiones

### Sesión 1. Del problema químico al modelo

En esta sesión se introduce el concepto de Machine Learning y se analiza cómo identificar problemas del área química que pueden abordarse mediante modelos de datos.

Se revisan ejemplos de:

* regresión;
* clasificación;
* agrupamiento;
* detección de anomalías;
* toma de decisiones basada en datos.

El objetivo es que el estudiante reconozca que Machine Learning no inicia con el algoritmo, sino con una pregunta técnica bien planteada.

---

### Sesión 2. Predicción de solubilidad acuosa usando SMILES, RDKit y regresión

Esta sesión aborda la predicción de la solubilidad acuosa de compuestos químicos a partir de su estructura molecular.

Se trabajan conceptos como:

* solubilidad acuosa;
* SMILES;
* RDKit;
* descriptores moleculares;
* QSPR;
* regresión lineal;
* K vecinos cercanos para regresión;
* métricas de evaluación como R², MAE y RMSE;
* dominio de aplicabilidad;
* sobreajuste e infraajuste.

El caso permite discutir cómo los modelos predictivos pueden ayudar a reducir tiempo, costos y recursos experimentales en la estimación de propiedades fisicoquímicas.

---

### Sesión 3. Clasificación de calidad de agua

En esta sesión se utiliza Machine Learning para clasificar muestras de agua a partir de variables fisicoquímicas.

Se trabajan conceptos como:

* clasificación supervisada;
* variable objetivo categórica;
* matriz de confusión;
* accuracy;
* precision;
* recall;
* F1-score;
* falsos positivos y falsos negativos.

El énfasis está en interpretar los resultados desde una perspectiva ambiental, reconociendo que los modelos pueden apoyar decisiones preliminares, pero no sustituyen la validación normativa o experimental.

---

### Sesión 4. Clustering para diseño exploratorio de nuevos materiales

Esta sesión introduce el aprendizaje no supervisado mediante clustering aplicado a materiales.

Se trabaja con datos reales de materiales y propiedades como el band gap experimental, número de elementos, fracción de oxígeno y fracción metálica.

Los estudiantes exploran cómo el agrupamiento puede ayudar a:

* identificar familias de materiales;
* reconocer patrones;
* seleccionar candidatos;
* apoyar el diseño exploratorio de nuevos materiales.

El enfoque es introductorio y evita modelos excesivamente complejos para facilitar la comprensión conceptual.

---

### Sesión 5. TinyML con Arduino Uno y emlearn

La sesión final muestra cómo un modelo de Machine Learning puede pasar de Python a un dispositivo físico.

Se trabaja un caso de monitoreo ambiental con variables como:

* temperatura;
* humedad;
* lectura de gas o calidad de aire.

Se entrena un modelo sencillo y se introduce el uso de **emlearn** para convertir modelos de Machine Learning a código C compatible con microcontroladores.

Esta sesión permite conectar el análisis de datos con aplicaciones de instrumentación, sensores y monitoreo ambiental.

---

## Herramientas utilizadas

Durante el curso se utilizan las siguientes herramientas:

* Python
* Google Colab
* pandas
* numpy
* matplotlib
* scikit-learn
* RDKit
* matminer
* pymatgen
* emlearn
* Arduino IDE

---

## Requisitos previos

Se recomienda que los estudiantes tengan conocimientos básicos de:

* química general;
* propiedades fisicoquímicas;
* fundamentos de ingeniería química o ambiental;
* uso básico de hojas de cálculo;
* interpretación de gráficas.

No es indispensable tener experiencia previa en Python, aunque sí es recomendable contar con disposición para trabajar con código guiado.

---

## Cómo usar los notebooks

Para trabajar con los notebooks:

1. Abrir el archivo `.ipynb` correspondiente.
2. Seleccionar la opción **Abrir en Google Colab**.
3. Guardar una copia en Google Drive.
4. Ejecutar las celdas en orden.
5. Completar las actividades y reflexiones incluidas en cada sesión.

En Google Colab, algunas bibliotecas pueden instalarse directamente dentro del notebook mediante comandos como:

```python
!pip install rdkit
```

o

```python
!pip install matminer pymatgen
```

dependiendo de la sesión.

---

## Productos esperados del estudiante

Al finalizar el curso, cada estudiante deberá contar con evidencias de trabajo que incluyan:

* clasificación de problemas de Machine Learning;
* análisis exploratorio de datos;
* modelos de regresión, clasificación y clustering;
* evaluación de modelos mediante métricas;
* interpretación ingenieril de resultados;
* reflexión sobre limitaciones y uso responsable;
* propuesta de aplicación de Machine Learning en un problema del área química.

---

## Uso en investigación educativa

Este curso puede utilizarse como base para una investigación educativa sobre la incorporación de Machine Learning en la formación de estudiantes de licenciatura del área química.

Algunos instrumentos sugeridos son:

* pretest diagnóstico;
* postest conceptual;
* encuesta de percepción estudiantil;
* rúbrica de evaluación de notebooks;
* análisis de productos de aprendizaje;
* preguntas abiertas para minería de textos.

Las respuestas abiertas pueden analizarse mediante:

* nubes de palabras;
* análisis de frecuencia;
* análisis de coocurrencias;
* categorización temática;
* análisis de sentimiento;
* comparación pretest-postest.

---

## Consideraciones éticas

El uso de los datos generados por estudiantes debe realizarse bajo criterios éticos de investigación educativa.

Se recomienda:

* informar a los estudiantes sobre el propósito académico e investigativo;
* solicitar consentimiento informado cuando corresponda;
* anonimizar las respuestas;
* evitar el uso de datos personales identificables;
* reportar resultados de manera agregada;
* aclarar que la participación en instrumentos de investigación no debe afectar la calificación académica.

---

## Licencia y uso del material

Este material puede utilizarse con fines educativos, académicos y de formación introductoria en Machine Learning aplicado al área química.

Se recomienda citar o reconocer la autoría del material cuando sea reutilizado, adaptado o compartido en otros cursos, talleres o investigaciones educativas.

---

## Autores
**Dr. César Eduardo Martínez Mercado**

Profesor Investigador 

Departamento de Ingeniería Química, Industrial y de Alimentos

Universidad Iberoamericana Campus Ciudad de México

**Dr. Jesús Andrés Arzola Flores**

Profesor Investigador

Facultad de Ingeniería Química

Benemérita Universidad Autónoma de Puebla

Áreas de interés:

* Machine Learning aplicado a ingeniería química
* Educación en ingeniería
* Inteligencia artificial generativa
* Modelado de propiedades fisicoquímicas
* Instrumentación y monitoreo ambiental
* Diseño de materiales
* Python aplicado a procesos químicos

---

## Nota final

Este curso busca acercar el Machine Learning a estudiantes del área química desde una perspectiva práctica, crítica y contextualizada.

El propósito no es formar especialistas avanzados en ciencia de datos en cinco sesiones, sino ofrecer una primera experiencia significativa que permita comprender cómo los datos, los modelos y la interpretación ingenieril pueden integrarse para resolver problemas reales del área química.
