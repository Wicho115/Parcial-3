# Entidades y atributos

### jugador
- id_jugador (***PK***)
- nombre
- fecha_nacimiento
- id_pais (***FK***)

### videojuego
- id_videojuego (***PK***)
- titulo
- fecha_salida
- desarroladora
- id_clasificacion (***FK***)

### plataforma
- id_plataforma (***PK***)
- nombre

### clasificacion
- id_clasificacion (***PK***)
- nombre
- edad_minima

### genero_juego
- id_genero_juego (***PK***)
- nombre

### pais
- id_pais (***PK***)
- nombre
- dominio

### jugador_x_videojuego_x_plataforma
- id_jugador_videojuego (***PK***)
- id_jugador (***FK***)
- id_videojuego (***FK***)
- id_plataforma (***FK***)

### videojuego_x_genero
- id_videojuego_genero (***PK***)
- id_videojuego (***FK***)
- id_genero (***FK***)

<br>

# Relaciones

1. Un **jugador** tiene un **pais** *(1-1)*
1. Un **jugador** tiene varios **videojuegos** *(1-M)*
1. Un **videojuego** tiene una **clasificacion** *(1-1)*
1. Un **videojuego** tiene varios **generos** *(1-M)*
1. Un **videojuego** tiene varias **plataformas** *(1-M)*

<br>

## ![Entidad-Relacion](https://media.discordapp.net/attachments/1025054668038090855/1035213960384876625/EntidadRelacion_SO.drawio.png?width=816&height=480)