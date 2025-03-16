# TP-1---Postman---Mattioda-Godoy
## TP 1 - Postman

### 1. Identificar cuantas peliculas tienen en su titulo "<ins>Cars</ins>".
> ### Ejecución: 
>   http://www.omdbapi.com/?i=tt3896198&apikey=174d845b&s=cars&type=movie
> ### Respuesta: 
>   "totalResults": "262"

### 2. Buscar "<ins>Hunger</ins>" y devolver el nombre de la ultima pelicula que retorna OMDb API.
> ### Ejecución:
>  http://www.omdbapi.com/?i=tt3896198&apikey=174d845b&t=hunger&type=movie
> ### Respuesta:
>  "Title": "Hunger"

### 3. Obtener de la pelicula <ins>"Monsters Inc."</ins>, la cantidad de votos de imdb, que actores actuaron y ver el Poster (un una nueva pagina).
> ### Ejecución: 
>  http://www.omdbapi.com/?i=tt3896198&apikey=174d845b&t=monsters, inc&type=movie
> ### Respuesta: 
>  "Actors": "Billy Crystal, John Goodman, Mary Gibbs"
>
>  "Poster": "https://m.media-amazon.com/images/M/MV5BMTY1NTI0ODUyOF5BMl5BanBnXkFtZTgwNTEyNjQ0MDE@._V1_SX300.jpg"
> 
>  "imdbVotes": "1,017,055"

### 4. Obtener de la pelicula <ins>"Rocky IV"</ins> su genero, su director y cuantos minutos de duración tiene la pelicula.
> ### Ejecución:
> http://www.omdbapi.com/?i=tt3896198&apikey=174d845b&t=rocky&type=movie
> ### Respuesta:
> "Runtime": "120 min",
> 
> "Genre": "Drama, Sport",
> 
> "Director": "John G. Avildsen"

### 5. Obtener de la pelicula cuyo imdbID es <ins>"tt0067992</ins> su titulo y el año en el que se estreno.
> ### Ejecución:
> http://www.omdbapi.com/?apikey=174d845b&i=tt0067992
> ### Respuesta:
> "Title": "Willy Wonka & the Chocolate Factory",
> 
> "Year": "1971"

## Poke

### 1. Obtener la información completa del Pokémon llamado <ins>Pikachu</ins>.
> ### Ejecución:
> https://pokeapi.co/api/v2/pokemon/pikachu
> ### Respuesta:
> mucho texto xd (12666 líneas para ser exactos)
### 2. Consultar cuantos <ins>tipos diferentes de Pokemon</ins> existen en la API.
> ### Ejecución:
> https://pokeapi.co/api/v2/type
> ### Respuesta:
> "count": 21
### 3. Obtener el nombre del Pokémon cuyo <ins>ID es 150</ins>.
> ### Ejecución:
> https://pokeapi.co/api/v2/pokemon/150
> ### Respuesta:
> "abilities": [
        {
            "ability": {
                "name": "pressure",
                "url": "https://pokeapi.co/api/v2/ability/46/"
            },
            "is_hidden": false,
            "slot": 1
        },
        {
            "ability": {
                "name": "unnerve",
                "url": "https://pokeapi.co/api/v2/ability/127/"
            },
            "is_hidden": true,
            "slot": 3
        }
    ]
 
### 4. Buscar los movimientos que puede aprender el Pokémon <ins>Charizard</ins>.
> ### Ejecución:
> https://pokeapi.co/api/v2/pokemon/charizard
> ### Respuesta:
> "abilities": [
        {
            "ability": {
                "name": "blaze",
                "url": "https://pokeapi.co/api/v2/ability/66/"
            },
            "is_hidden": false,
            "slot": 1
        },
        {
            "ability": {
                "name": "solar-power",
                "url": "https://pokeapi.co/api/v2/ability/94/"
            },
            "is_hidden": true,
            "slot": 3
        }
    ]

### 5. Obtener la <ins>altura y peso</ins> del Pokémon llamado <ins>Bulbasaur</ins>.
> ### Ejecución:
> https://pokeapi.co/api/v2/pokemon/bulbasaur
> ### Respuesta:
> "weight": 69
>
> "height": 7

### Trabajo hecho por: Tiziana Emma Mattioda y Bruno Godoy.
