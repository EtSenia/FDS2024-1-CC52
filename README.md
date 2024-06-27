# Trabajo Final Grupo 4

## Objetivo del Proyecto
El propósito de este proyecto es aplicar una metodología rigurosa para el análisis y la extracción de valor a partir de un conjunto de datos, utilizando CRISP-DM (Proceso Estándar Intersectorial para la Minería de Datos). 
Mediante este enfoque, buscamos transformar datos en información valiosa que pueda informar y respaldar decisiones estratégicas respondiendo las preguntas correspondientes.

## Nombre de los Alumnos Participantes
- Eduardo José Rivas Siesquén - U202216407
- Rodrigo Alonso Ramírez Cesti - U202210690
- Joe Maicol Turpo Queque	 -	U202124254
- Guido Yair Abel Jeri Saldaña	-	U202219322

## Descripción del Conjunto de Datos
El conjunto de datos utilizado en este proyecto incluye información sobre videos, tales como:
NOMBRE DEL ATRIBUTO | DESCRIPCIÓN DEL ATRIBUTO | TIPO DEL ATRIBUTO
--|--|--|
video_id|Identificador interno del video dentro de Youtube|Categórico
trending_date|Fecha en la que el video llegó a ser tendencia en Youtube. Formato yy.dd.mm |Numérico
title|Título del video |Categórico
channel_title|Nombre del canal que subió el video|Categórico
category_id|Identificador de la categoría principal del video|Numérico
publish_time|Fecha y hora de la publicación del video.|Numérico/Categórico
tags|Etiquetas del video, sirven como categorías menores o “palabras clave”|Categórico
views|Numerosos de vistas que tiene el video|Numérico
likes|Cantidad de likes que tiene el video|Numérico
dislikes|Cantidad de dislikes que tiene el video|Numérico
comment_count|Cantidad de comentarios que tiene el video|Numérico
thumbnail_link|Link que muestra la foto de la miniatura del video|Categórico
comments_disabled|Si el video tiene los comentarios activados o desactivados|Categórico
ratings_disabled|Si es que el video permite mostrar la cantidad de likes/dislikes|Categórico
video_error_or_removed|Si es que el link del video no funciona o si es que el video ha sido retirado de la pagina|Categórico 
description|Descripcion del video|Categórico 
state|Estado o región de donde proviene del video (incorporado aleatoriamente)|Categórico 
lat|Latitud geográfica de ubicación del Estado o región|Numérico
lon|Longitud geográfica de ubicación del estado o región|Numérico
geometry|Coordenadas geométricas de la ubicación del estado o región|Numérico

## Conclusiones
**¿Qué categorías de videos son las de mayor tendencia?**
- En general, las categorías que tienden a ser tendencia más frecuentemente son: “Entertainment” (Entretenimiento), “People and Blogs” (Personas y Blogs), y “Sports” (Deportes).

**¿Qué categorías de videos son los que más gustan?**
- La categoría con más likes es la de “Music” (Música), seguida cercanamente por la categoría “Entertainment” (Entretenimiento).

**¿Qué categorías de videos son los que menos gustan?**
- La categoría con más dislikes es la de “Entertainment” (Entretenimiento), seguida cercanamente por la categoría “Music” (Música).

**¿Qué categorías de videos tienen la mejor proporción (ratio) de “Me gusta”/“No me gusta”?**
- La categoría de “Education” tiene el mejor ratio de likes/dislikes, con 1 dislike cada 42 likes aprox. Le sigue “Autos & Vehicles” con un ratio de 1/35, y “Film & Animation” con un ratio de 1/33.

**¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas”/”Comentarios”?**
- La categoría con el ratio más grande de vistas/comentarios es la categoría de “Sports”, con 1 comentario cada 400 vistas, de ahí hay un salto considerable a la categoría “Pets & Animals”, con aprox. 200 vistas cada comentario.

**¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?**
- Los mayores picos de volumen de vistas de videos en tendencia a lo largo del tiempo ocurrieron alrededor de diciembre 2017, marzo 2018 y mayo 2018.

**¿Qué canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia?**
- Los canales “Cracks”, “Badabun”, “Cracks MX”, “Televisa Telenovelas”, “El Salvador 4K”, “Las Estrellas”, “Troom Troom Es”, “Tu COSMOPOLIS”, “Azteca Novelas” y “Genial” son los canales con más frecuencia de videos en tendencia.
- Hay muchos canales que solo tienen un video en tendencia, y por lo tanto empatan en el último lugar de la lista.

**¿En qué Estados se presenta el mayor número de “Vistas”?**
- El estado con mayor número de vistas es Baja California, seguido por Coahuila y Guerrero.

**¿En qué Estados se presenta el mayor número de “Me gusta” y “No me gusta”?**
- Los estados con mayor cantidad de “Me gusta” son: Coahuila, Sonora y Baja California.
- El estado con la mayor cantidad de “no me gusta” es Veracruz, seguido de lejos por Coahuila y Tlaxcala.

**¿Es factible predecir el número de “Vistas”, “Me gusta” o “No me gusta”?**
- Con regresión logística, hay una precisión del 2% cuando se intenta predecir la cantidad de “vistas”, “me gusta” y “no me gusta”.

**¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben?**
- La base de datos no nos proporcionó información acerca del contenido de los comentarios, por lo tanto, no podemos responder esta pregunta utilizando la Ciencia de Datos actualmente.


## Licencia de Uso
Este proyecto está licenciado bajo la Licencia MIT.

