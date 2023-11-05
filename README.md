# TextMining

En este problema se trabaja con un conjunto de datos reales publicados para la shared-task ProfNER, celebrada en el año 2021. Específicamente, se utilizarán los datos textuales de la subtarea 1, centrada en la clasificación de textos. Este conjunto de datos son tweets en español que tienen asignada una etiqueta numérica, que representa la presencia (valor 1) o no (valor 0) de menciones de profesiones en el tweet. Por si fuera de tu interés, el proceso de obtención, selección y anotación de datos está descrita en este enlace: https://colab.research.google.com/corgiredirector?site=https%3A%2F%2Ftemu.bsc.es%2Fsmm4h-spanish%2F%3Fp%3D4003

Se entrenan diferentes modelos de clasificación que permitan clasificar correctamente los tweets. Para ello se crean y utilizan las funciones de preprocesado de datos, se aplican estrategias de vectorización de trextos como TF-IDF o embeddings, y entrenan/evaluan modelos de clasificación. 
