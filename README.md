# Analisis exploratorio de las variables en relación a los Spoilers en comentarios de IMDB

# Abstract
Como a la mayoría de las personas, no nos gustan los spoilers de las películas que nos interesan ver y nos gustaría evitarlos a toda costa. Consideramos que debería existir un mecanismo para evitarlos en sitios como las redes sociales o páginas de reseñas. Por esto nos motivó la idea de crear un modelo que permita identificar si un comentario contiene un posible spoiler o no, para de esta manera filtrarlos o evitarlos al momento de navegar por internet. Para esta tarea usaríamos IMDB Spoiler Dataset y algún otro complementario como fuente de datos para entrenar a nuestro modelo. El modelo debería ser capaz de indicarnos si en una frase o comentario existe una posibilidad de spoiler en el contenido, además de esto, con este proyecto buscamos descubrir información nueva de las relaciones que pueden existir entre los datos de las películas y la cantidad de spoilers que presenten en su feed.

# Research questions
- Conocer las relaciones de los actores con la cantidad de spoilers de una película.
- Conocer las relaciones del género con la cantidad de spoilers de una película.
- Conocer las palabras más frecuentes en comentarios con spoilers.
- Conocer las relaciones de otras posibles variables de spoilers de una película.

# Dataset

- IMDB Spoiler Dataset (967 MB)
- IMDb movies extensive dataset (230 MB)
- IMDb Largest Review Dataset (7.78 GB)

Para el procesamiento de datos, esperamos poder combinar la información de estos datasets (y talvez incluir otros en el futuro) para obtener unos datos completos. Con este merge tendríamos no solo los datos básicos como el nombre, las descripciones y los actores, sino que también contaríamos con los datos de los comentarios y si estos contienen o no spoilers. Luego procederíamos con la limpieza de datos, descartando todos los datos incompletos y corrigiendo algunos si es que tienen inconsistencias menores.

Contamos con archivos en formato .json y .csv que tendriamos que manejar para usar ambos en conjunto, además tenemos algunos archivos de gran tamaño que dividiremos en muestras más pequeñas y manejables por cuestiones de espacio.

# A list of internal milestones up until project milestone 2
- Creación del repositorio.
- Obtención y lectura de datos.
- Pruebas con un subsampling de 100 elementos.

# Questions you need help with
- ¿Cual sería el mejor modo de hacer subsampling? Sobretodo para el archivo de 7.78 GB
- ¿Qué algoritmos nos sugiere para el proyecto?
- ¿Qué otros insights nos recomendaria buscar?
