# Entidades y atributos

### jugador
- jugador_id (***PK***)
- nombre
- fecha_nacimiento
- pais_id (***FK***)

### videojuego
- videojuego_id (***PK***)
- titulo
- fecha_salida
- precio
- id_clasificacion (***FK***)

### jugador_x_videojuego_x_plataforma
- id_jugador_videojuego (***PK***)
- id_jugador (***FK***)
- id_videojuego (***FK***)
- id_plataforma (***FK***)

### videojuego_x_genero
- id_videojuego_genero (***PK***)
- id_videojuego (***FK***)
- id_genero (***FK***)

### plataforma
- plataforma_id (***PK***)
- nombre

### clasificacion
- clasificacion (***PK***)
- nombre
- edad_minima

### genero_juego
- id_genero (***PK***)
- nombre

### pais
- pais_id (***PK***)
- nombre
- dominio