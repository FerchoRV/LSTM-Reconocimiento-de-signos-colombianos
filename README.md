# ANEXO 2 Código fuente

Este anexo registra la parte experimental de las actividades 1 y 2 de la Fase 2 del proyecto “Intérprete de lenguaje de signos colombiano para apoyar procesos de comunicación directa entre personas sordas y oyentes ”  se encuentra organizado en carpetas de la siguiente manera:

-	**Datasets:** Contiene la información de extracción de puntos de control para cada uno de los dataset creados hasta el momento del lenguaje de signos colombiano que son la fuente de datos para entrenar las estrategias de aprendizaje profundo que se reportan en la literatura.

-	**Entrenamiento modelos:** Esta carpeta contiene los cuadernos de jupyter en donde se experimenta con cada uno de los datasets obtenidos, además se encuentra las dos estrategias de extracción de puntos de control que se reporta en el artículo de investigación denominado "Fortaleciendo el Reconocimiento de Lenguaje de Signos Colombiano usando modelos de Aprendizaje Profundo.".

-	**Gráficos:** Contiene las imágenes del comportamiento de la métrica, precisión y función de pérdida de cada uno de los entrenamientos realizados. 

-	**Modelos:** Contiene los modelo obtenidos en la etapa de entrenamiento y experimentación del proyecto se encuentran tres modelos obtenidos hasta ahora uno para el abecedario (actionAbecedario.h5) colombiano, otro capaz de reconocer 19 palabras básicas (actionPalabras.h5) y por ultimo está el modelo que reconoce un total de 28 signos básicos colombianos (actionPalabrasV2.h5)

-	**Prueba tiempo real:** Contiene un cuaderno de jupyter el cual permite cargar los modelos entrenados y hacer pruebas de detección de signos colombiano en tiempo real.

Adjunto a esta información también comparto un enlace el cual lleva a una carpeta de acceso libre compartida de algunas pruebas de detección de signos colombiano en tiempo real.

**Pruebas tiempo real:** https://drive.google.com/drive/folders/1iGG54aZw0ZHs6ThBYGFU2_HXfooUtFB2?usp=sharing
