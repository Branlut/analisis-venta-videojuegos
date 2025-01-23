# Análisi de venta de videojuegos

## Descripción
La tienda online ice la cual vende video juegos alrededor del mundo y tiene a su disposicion la informacion de la ventas que se han realizado desde 1980 hasta el 2016, no solo se cuenta con la venta de videosjuegos por region como tal (na,eu.jp y otros) si no que tambien cuentan con las plataformas en que salieron los juegos su genero, la clasificacion de la Junta de clasificación de software de entretenimiento (edad recomendada para jugar) y las reseñas de estos tanto de prensa especializada como de usuarios normales.

## Objetivo
Se nos encargo encontrar tendencias o patrones a la hora de comprar juegos si existen preferencias por alguna platforma, si se tiene preferencia por un genero es especial si la reseñas afectan las compras y si estos difieren de region en region. Todo esto para enfocarse en los juegos que seran mas rentables para el año 2017. 

## Tecnologias
- Python
- Vs code
- pandas
- numpy
- scipy
- math
- matplotlib
- seaborn

## Análisis
### ventas por plataforma
- Las plataformas como mejores ventas fueron la PS4,PS3,X360,3DS,XOne

- Se puede apreciar que las plataformas de playstation son las que poseen mayores ventas para los años vistos

- Las plataformas preferentes son las de Sony ya que posee tanto la PS3 y la PS4 en la lista, le sigue Microsoft con la Xbox 360 y la Xbox One y por ultimo nintendo con la 3DS

- En general la vida util dependera de que tan popular sea la plataforma por lo que se puede apreciar cuando es popular tiene una vida util de al menos 4 años

- Las plataformas que no tuvieron ventas el año 2016 fueron la PSP Y la DS

- Las plataformas posiblemente mas rentables por el periodo en que salieron y las compañias que generalmente las respaldan(Sony,nintendo,Microsoft) son WiiU, PS4 Y Xbox One

- Con respecto a lo anterior se debe considerar en este ambito en particular la plataforma PC ya que hace referencia al equipo computacional como tal por lo cual en el contexto de los videojuegos siempres sera relevante y rentable considerar esta opcion

### Correlación entre reseñas y ventas
- Como se puede ver en el gráfico de dispersión las reseñas positivas si afectan las ventas pero se toma mas peso por las reseñas de los propios jugadores que por la critica especializada

- Lo planteado anteriormiento se puede evidenciar por la correlación que tiene las reseñas de los usuario con los ventas totales ya que hay una correlacion entre el user score y las ventas totales superior a la de critic score

### Comparacion de juegos en otras plataformas
- Por lo general se suele preferir jugar en las plataformas PS3 y Xbox 360 por lo que se puede apreciar en el grafico hay que considerar el genero del juego ya que en este caso la 3DS es una consola portatil y puede preferir ciertos juegos para esta por ejemplo

### Juegos por genero
- Se suele preferir juegos que requieren que el jugador realice muchas acciones con el control esto se ve reflejado ya que el genero mas vendido es el de accion y el menos preferido el de estrategia los cuales son mas complejos y contienen acciones automaticas por lo que el judador no interactua tanto con los controles

## Hipótesis

### Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.
Hipotesis nula: Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son iguales

Hipotesis alternativa: Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son diferentes

- Utilizando la prueba correspondiente para comprobar si las medias estasdisticas son iguales se pudo comprobar que las reseñas de los usuarios de Xbox One y PC casi iguales

- Esto se sustento al hacer la prueba de levene que muestra si las varianzas son iguales y los  resultados tambien condujeron al rechazo el no poder rechazar H0

- Por lo visto los usuarios de estas plataformas tienen una opinion similar con respecto a los juegos, puede ser debido a que cuentan con los mismos juegos 


### Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes

Hipotesis nula: Las califiaciones promedio de los usuarios para los generos de accion y deportes son iguales.

Hipotesis alternativa: Las calificaciones promedio de los usuarios para los generos de accion y deportes son diferentes

- Utilizando la prueba correspondiente para comprobar si las medias estasdisticas son iguales se pudo comprobar que las reseñas de los usuarios para los generos de accion y deportes es diferente. 

- Esto se sustento al hacer la prueba de levene que muestra si las varianzas son iguales y los  resultados tambien condujeron al rechazo de H0

- Al parecer los usuarios no tienen el mismo gusto por los juegos de accion y deportes, puede tener relacion al rating por edad ya que los juegos de deportes pueden ser catalagados para los mas pequeños ya que no incluyen mucha violencia lo que puede no interesar a los mas grandes

# Conclusiones 
- El favoritismo se vio sobre las consolas como Playstation, Xbox y Nintendo

- Con respecto al punto anterior en el ambito de los videojuegos la plataforma PC como esta descrita en el dataframe siempre se debe tener en consideracion

- Las personas tiene un genere que prefieren el cual es el de accion de manera general y luego por region por lo menos fue el preferido por Norte America y Europa y segundo mejor en el caso de Japon

- Como se mencionan en el punto anterior tanto las preferiencias con respecto a la plataforma como el genero las regiones de Norte America y Europa tiene tendencias muy parecidas.

- Con respecto al genero de accion esto se puede evidenciar en la comparacion de los mismos juegos en otras plataformas en la cual la moyoria son del genero accion

- Japon por otra parte cuenta con otras preferencias un tanto diferentes en cuanto a plataforma y genero preferidos.

- Se puede evidenciar que las reseñas de los juegos influencia su compra en mas medida las de los propios usuarios

- Los jugadores tienden a preferir juegos con rating(categoria de edad recomendada para un juego) de M lo que quiere decir que estan interesados en juegos que pueden contener violencia, escenas de sangre, etc/ 

- Por los datos anteriores se puede concluir que los juegos mas rentables seran los de genero accion ya que es una gran preferencia en las 3 regiones estudiadas, en cuanto a las plataformas se vio una tendencia hacia las marcas Playstation, Xbox y nintendo, por lo que la PS4,Xbox One y Nintendo WiiU son las plataformas a considerar para futaras ventas
