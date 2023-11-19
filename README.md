# ACREACIÓN DE CONOCIMIENTO APLICANDO LA METODOLOGÍA CRISP-DM
# Integrantes
* Claudia Letizia Sifuentes Mendieta
* Renato Guillermo Vivas Alejandro
* Ayrton Jafet Samaniego Millan
# Objetivo
El objetivo del proyecto es conocer las tendencias de los videos de YouTube en el país de Alemania y obtener conocimiento aplicando tecnicas de mineria de datos y machine learning
# Dataset
<table>
    <thead>
        <tr class="rowsep-1">
            <th scope="col"><strong>Variable</strong></th>
            <th scope="col"><strong>Tipo</strong></th>
            <th scope="col"><strong>Descripción</strong></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row"><em>video_id</em></th>
            <td>Categórico</td>
            <td>Id del video en youtube</td>
        </tr>
        <tr>
            <th scope="row"><em>trending_date</em></th>
            <td>Numérico</td>
            <td>Hora en que el video es tendencia</td>
        </tr>
        <tr>
            <th scope="row"><em>title</em></th>
            <td>Categórico</td>
            <td>Titulo del video</td>
        </tr>
        <tr>
            <th scope="row"><em>category_id</em></th>
            <td>Categórico</td>
            <td>Id de la categoría del video</td>
        </tr>
        <tr>
            <th scope="row"><em>publish_time</em></th>
            <td>Fecha</td>
            <td>Fecha y hora en la que se publico el video</td>
        </tr>
        <tr>
            <th scope="row"><em>tags</em></th>
            <td>Categórico</td>
            <td>Tags etiquetados en el video</td>
        </tr>
        <tr>
            <th scope="row"><em>views</em></th>
            <td>Entero</td>
            <td>Cantidad de visitas</td>
        </tr>
        <tr>
            <th scope="row"><em>likes</em></th>
            <td>Entero</td>
            <td>Cantidad de me gusta</td>
        </tr>
        <tr>
            <th scope="row"><em>dislikes</em></th>
            <td>Entero</td>
            <td>Cantidad de no me gusta</td>
        </tr>
        <tr>
            <th scope="row"><em>comment_count</em></th>
            <td>Entero</td>
            <td>Cantidad de comentarios</td>
        </tr>
        <tr>
            <th scope="row"><em>thumbnail_link</em></th>
            <td>Categórico</td>
            <td>Link de la miniatura del video</td>
        </tr>
        <tr>
            <th scope="row"><em>comments_disabled</em></th>
            <td>Booleano</td>
            <td>Indica si los comentarios en el video están desactivados o no</td>
        </tr>
        <tr>
            <th scope="row"><em>ratings_disabled</em></th>
            <td>Booleano</td>
            <td>Indica si las calificaciones en el video están desactivados o no</td>
        </tr>
        <tr>
            <th scope="row"><em>video_error_or_removed</em></th>
            <td>Booleano</td>
            <td>Indica si el video tiene errores o fue borrado de la plataforma</td>
        </tr>
        <tr>
            <th scope="row"><em>description</em></th>
            <td>Texto</td>
            <td>Descripcion del video</td>
        </tr>
        <tr>
            <th scope="row"><em>state</em></th>
            <td>Categórico</td>
            <td>Estado donde el video fue publicado</td>
        </tr>
        <tr>
            <th scope="row"><em>lat</em></th>
            <td>Numérico</td>
            <td>Longitud del estado donde fue publicado</td>
        </tr>
        <tr>
            <th scope="row"><em>lon</em></th>
            <td>Numérico</td>
            <td>Latitud del estado donde fue publicado</td>
        </tr>
        <tr>
            <th scope="row"><em>geometry</em></th>
            <td>Coordenada</td>
            <td>Coordenadas del estado donde fue publicado</td>
        </tr>
    </tbody>
</table>

# Conclusiones
Conlusiones por pregunta
* ¿Qué categorías de videos son las de mayor tendencia?
Las categorías de los vídeos guardan una estrecha relación con la tendencia y se demuestra que la categoría de entretenimiento es la más consumida por el público general.
* ¿Qué categorías de videos son los que más gustan? ¿Y las que menos gustan?
Las categorías que tienen más likes son todas aquellas relacionadas con el disfrute como lo son los videos con la categoría de “Music” y “Entertainment” que también son las que son más consumidas. Por otro lado las categorías que tienen la menor cantidad de me gusta son “Movies” y “Shows”, esto puede deberse a varios factores uno de ellos siendo la cantidad de vistas que tienen y otro debido a la poca costumbre que se tiene de dar like a este tipo de videos.
* ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Me gusta” / “No me gusta”?
Se destaca que las categorías de videos que muestran la mejor proporción de "me gusta" y "no me gusta" son "Pets & Animals", "Autos & Vehicles", "Education" y "Travel & Events", categorías que tienden a ofrecer contenido que es percibido como entretenido, informativo o educativo, generando más "me gusta". En contraste, las categorías con la peor proporción, que incluyen "News & Politics", "Shows" y "Trailers", suelen abordar temas controvertidos o polarizantes que puede resultar en una mayor proporción de "no me gusta" por parte de los espectadores. Estos resultados resaltan la importancia de comprender las preferencias y reacciones del público en diferentes categorías de videos, lo que puede ser útil para creadores de contenido y estrategias de marketing digital en YouTube. Enfocarse en áreas con altas proporciones de "me gusta" puede ser beneficioso para aumentar la satisfacción del espectador y el atractivo del contenido.
* ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas” / “Comentarios”?
En Alemania, los videos de "Movies", "Shows" y "Sports", generan más comentarios que los videos de otras categorías, como "Gaming" y "Pets & Animals". Esto sugiere que las empresas de marketing digital pueden aprovechar estas tendencias creando contenido de estas categorías.
* ¿En qué categorías de videos predomina el sentimiento positivo y negativo en los títulos del video según las estaciones del año?
Los títulos de vídeos de entretenimiento suelen ser más positivos que los de otras categorías, mientras que los títulos de vídeos de noticias suelen ser más negativos. Esto sugiere que los usuarios buscan diversión en el entretenimiento y análisis en las noticias.
* ¿Existe alguna relación entre la cantidad de comentarios con la polaridad de sentimiento que tiene la descripción del video?
Los videos con descripciones positivas reciben más comentarios que los videos con descripciones negativas o neutrales. Esto se debe a que los usuarios de YouTube están más inclinados a comentar videos que les resultan atractivos o interesantes. Las descripciones positivas sugieren contenido divertido, entretenido o informativo, incentivando la participación de los usuarios. Por otro lado, las descripciones negativas o neutrales suelen ser menos atractivas, disminuyendo la probabilidad de recibir comentarios.
* ¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?
El análisis del gráfico evidencia una notoria disminución en la cantidad de videos en tendencia, alcanzando su punto máximo en marzo con 6,059 videos y experimentando desde entonces una caída constante, que representa una disminución de más del 90%. Este patrón sugiere cambios sustanciales en la dinámica de la plataforma de YouTube, lo que podría tener implicaciones significativas para los creadores de contenido que buscan alcanzar una audiencia más amplia mediante la aparición en la página de tendencias.
* ¿Qué canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia?
El análisis muestra una clara tendencia en la página de tendencias de YouTube, donde los canales como Galileo, Ruhrpottwache, Cukur y Auf Streife, que se centran en contenido de entretenimiento, son recurrentes. Por otro lado, canales como VOA Persian Ofogh, Rabea Schmale y Lina Ciupka tienden a tener una presencia menor en la página de tendencias. Esta disparidad sugiere que el contenido de entretenimiento tiene más probabilidad de destacar y ser promovido en la plataforma, mientras que otros temas o estilos pueden encontrar más desafíos para llegar a la página de tendencias.
* ¿En qué Estados se presenta el mayor número de “Vistas”, “Me gusta” y “No me gusta”?
Al observar los datos, se nota una correlación entre la tendencia en visitas y la cantidad de "me gusta" y "no me gusta". En términos generales, los estados de "Thüringen" y "Hamburgo" destacan como los principales en las gráficas de "vistas", "me gusta" y "no me gusta". Estos estados son seguidos de cerca por otros como "Hessen" y "Schleswig Holstein". Estos hallazgos sugieren una relación consistente entre la popularidad de un estado en términos de visitas y su interacción a través de "me gusta" y "no me gusta" en la plataforma.
* ¿Es factible predecir el número de “Vistas” o “Me gusta” o “No me gusta”?
Debido a la naturaleza de nuestro dataset no podemos predecir el número de visitas, likes o dislikes que pueda tener un video, pero podemos predecir que tan bien le va a ir al video. Esto es logrado con la categorización de las visitas, likes y dislikes estableciendo ciertos parámetros de evaluación para categorizar los datos antes numéricos dentro de los umbrales “Bajo”, “Medio”, “Alto” y “Muy Alto”.
* ¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben?
Actualmente no podemos determinar si los videos en tendencia son los que reciben la mayor cantidad de comentarios positivos, ya que no disponemos de datos específicos sobre los comentarios (positivos o negativos) para realizar un análisis detallado. La ausencia de información detallada sobre los comentarios limita nuestra capacidad para evaluar la naturaleza de las interacciones en los videos en tendencia.

Conclusiones del proyecto
* Al revisar detalladamente cada fase del proyecto se considera que se puede mejorar la fase de preparación de los datos por que los datos numéricos tan grandes de 8 cifras fueron el verdadero problema para responder la pregunta 10.
* Se podría optar por mejores algoritmos de machine learning para ambos modelos de regresión y clasificación, como regresión lineal, regresión logística, árboles de decisión, etc.
* Se debería mejorar la comunicación en el equipo.

# Licencia
Se ha acordado usar para este proyecto analítico la licencia [Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)
