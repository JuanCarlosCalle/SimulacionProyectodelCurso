# SimulacionProyectodelCurso
Modelos y Simulacion II: Proyecto del Curso


## Juan Carlos Calle - 1039452184,
## Andrés Quintero Bedoya - 1216727950,
#### Prof. Julian David Arias Londoño
##### Departamento de Ingeniería de Sistemas ,
##### Universidad de Antioquia, Colombia

# Retinopatía diabética: detección de ceguera

# Título del Proyecto

### APTOS 2019 Ceguera

La retinopatía diabética es una enfermedad que afecta la retina del ojo. Millones en todo el mundo sufren de esta enfermedad.

Actualmente, el diagnóstico ocurre mediante el uso de una técnica llamada fotografía de fondo de ojo, que consiste en fotografiar la parte posterior del ojo.

El examen médico para la retinopatía diabética se produce en todo el mundo, pero es más difícil para las personas que viven en zonas rurales.

Mediante el aprendizaje automático y la visión por computadora, intentamos automatizar el proceso de diagnóstico, que actualmente se realiza de forma manual por los médicos. 

En Kaggle (https://www.kaggle.com/c/aptos2019-blindness-detection/data  tendremos acceso a un conjunto de datos de decenas de miles de imágenes clínicas del mundo real de pacientes sanos y patentes con la enfermedad, y etiquetadas por médicos capacitados.

Con este conjunto de datos, podremos entrenar un modelo de aprendizaje automático para lograr un alto nivel de precisión al predecir la aparición de la enfermedad en pacientes.


## Contenido: 📋

El siguiente cuaderno se ha organizado de la siguiente manera:

El código se ha enumerado inicialmente primero, y se ha dividido aproximadamente en las siguientes partes clave. Vale la pena revisar este código y, a medida que lea la siguiente sección principal de discusión del experimento, puede consultar la sección del código según corresponda.

# Resumen

El siguiente es un resumen de cómo abordé el problema y está más o menos en el orden de cómo aborde el proyecto. En cada etapa, el objetivo era encontrar la mejor configuración que me permitiera avanzar en cada experimento, y pasé mucho tiempo conociendo los datos, la línea de base y tratando de descubrir errores durante el proceso de capacitación.

Aproximadamente, el orden de las operaciones para este proyecto se detalla a continuación:

1. Importacion y configuracion
2. Bases de procesamiento de imágenes
3. Análisis exploratorio de datos
4. Agregar/eliminar Datos
5. Extraccion de caracteristicas
6. metodologıa de validacion
7. Analisis individual
8. Extraccion de caracterısticas por el metodo PCA
9. Resultados

### Experimentos 🔧


*   Naıve Bayes
*   K vecinos mas cercanos
*   Redes Neuronales Artificiales
*   Random Forest
*   Maquinas de Soporte Vectorial con kernel lineal y con kernel RBF.



### Cosas que no intentamos

-   Redes neuronales convolucionales
-   Kapa Cohen

# Para abrir el codigo abrir el archivo trabajo_principal.ipyn

## Autores ✒️
* **Juan Carlos Calle** 
* **Andrés Quintero Bedoya** - *Documentación* - [fulanitodetal](#fulanito-de-tal)
