# TFM_Trail_Analytics
En este repositorio se almacena el código desarrollado para el proyecto "Trail Analytics: Exploración visual y modelado predictivo de carreras por montaña" englobado dentro del trabajo final del Máster de Ciencia de Datos de la Universitat Oberta de Catalunya (UOC).

En este archivo se resumen varios aspectos: la estructura creada y los pasos a seguir para la ejecución de cada uno de los scripts, en caso de querer replicar los resultados.

# Estructuración del código

El origen del estudio se basa en los datos de actividades deportivas provenientes del aplicativo Strava e implicadas en 11 corredores de diversa categoría, edad y sexo. Concretamente se hace uso de dos tipos de ficheros en formato de tercer nivel .csv llamados "Activities_NumeroCorredor" y "profile_NumeroCorredor". Los podremos localizar dentro de la subcarpeta "Exportacion_noviembre" de la carpeta raíz "Datos".

El archivo principal de ejecución es "TrailAnalytics_TFM_Joraddo.Rmd" el cual se ejecuta bajo el lenguaje R mediante la herramienta RStudio. Dentro de este se desarrolla toda la metodología aplicada para tratar de resolver y responder a preguntas planteadas con objetivo de completar un proceso de minería de los datos propuestos contando a su vez la historia ligada a estos. El notebook se encuentra configurado para poder exportarse de forma dinámica usando una plantilla modelo llamada "TrailAnalytics_TFM_Joraddo.html", por su parte "TrailAnalytics_GAM.Rmd", como documento extendido del primero, se ejecuta bajo shiny para poder usar los gráficos y aplicaciones interactivas desarrolladas en él. 
Asimismo, y a modo de ofrecer su disponibilidad y uso completo, se ha publicado en el siguiente link : https://joraddo.github.io/TFM_Trail_Analytics/TrailAnalytics_TFM_Joraddo.html

Finalmente se aportan dos ficheros más dentro del directorio "Datos": 

  - Activities_final_Analysis.csv : se trata del conjunto de datos ya fusionado y limpio con el que se han generado los gráficos y modelos predictivos finales implicados en la fase de análisis.
  - 5622375873.fit: se trata de una muestra de un fichero que contiene la información relacionada con la localización de la ruta o actividad punto por punto junto con     información meteorológica adicional. Hablamos de un fichero propuesto para líneas futuras del trabajo.


