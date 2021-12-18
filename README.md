# Analisis exploratorio de las variables en relación a los Spoilers en comentarios de IMDB

# Resumen
Como a la mayoría de las personas, no nos gustan los spoilers de las películas que nos interesan ver y nos gustaría evitarlos a toda costa. Consideramos que debería existir un mecanismo para evitarlos en sitios como las redes sociales o páginas de reseñas. Por esto nos motivó la idea de crear un modelo que permita identificar si un comentario contiene un posible spoiler o no, para de esta manera filtrarlos o evitarlos al momento de navegar por internet. Para esta tarea usaríamos IMDB Spoiler Dataset y algún otro complementario como fuente de datos para entrenar a nuestro modelo. El modelo debería ser capaz de indicarnos si en una frase o comentario existe una posibilidad de spoiler en el contenido, además de esto, con este proyecto buscamos descubrir información nueva de las relaciones que pueden existir entre los datos de las películas y la cantidad de spoilers que presenten en su feed.

# Pregunta de investigación
- Conocer las relaciones de los actores con la cantidad de spoilers de una película.
- Conocer las relaciones del género con la cantidad de spoilers de una película.
- Conocer las palabras más frecuentes en comentarios con spoilers.
- Conocer las relaciones de otras posibles variables de spoilers de una película.

# Dataset
- IMDB Spoiler Dataset (967 MB). Encontrado en: https://www.kaggle.com/rmisra/imdb-spoiler-dataset
- IMDb movies extensive dataset (230 MB). Encontrado en: https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset?select=IMDb+movies.csv

Para el procesamiento de datos, esperamos poder combinar la información de estos datasets (y talvez incluir otros en el futuro) para obtener unos datos completos. Con este merge tendríamos no solo los datos básicos como el nombre, las descripciones y los actores, sino que también contaríamos con los datos de los comentarios y si estos contienen o no spoilers. Luego procederíamos con la limpieza de datos, descartando todos los datos incompletos y corrigiendo algunos si es que tienen inconsistencias menores.

Contamos con archivos en formato .json y .csv que tendriamos que manejar para usar ambos en conjunto, además tenemos algunos archivos de gran tamaño que dividiremos en muestras más pequeñas y manejables por cuestiones de espacio.

# Lista de metas a conseguir hasta el milestone 2
- Creación del repositorio.
- Obtención y lectura de datos.
- Pruebas con un subsampling de 100 elementos.

# Preguntas con las que se necesitan ayuda
- ¿Cual sería el mejor modo de hacer subsampling? Sobretodo para el archivo de 7.78 GB
- ¿Qué algoritmos nos sugiere para el proyecto?
- ¿Qué otros insights nos recomendaria buscar?

# Ejecutar el programa
## 1. Obtener los datos
Descargar los datasets previamente mencionados:
- IMDB Spoiler Dataset (967 MB).
- IMDb movies extensive dataset (230 MB).

## 2. Guardar los datasets
1. Crear una carpeta llamada "data" en el mismo directorio donde se encuentra el notebook.
2. Creamos 2 carpetas más dentro de "data" llamadas "movies" y "movies_info"
2. Descomprimir los datasets.
3. Guardar los datasets descomprimidos del primer link en las carpetas "data/movies".
4. Guardar los datasets descomprimidos del segundo link en las carpetas "data/movies_info".

## 3. Correr el notebook
Re compila el kernel y observa los resultados por tu cuenta.