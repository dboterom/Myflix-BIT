# Myflix
## Trabajo autónomo de la tercera semana

Para este trabajo deberás tener en cuenta lo siguiente:

- Dentro del archivo "index.html" tienes 3 div, cada uno con su ID. Esto servirá para identificar y crear las clases que vayas a utilizar en css.
- También existe dentro del div con ID "movies-list" un div con su propio ID que servirá para identificar y crear las clases de css necesarias para darle formato al contenedor de una película.
- Dentro de la carpeta "css" tienes un archivo por cada ID en el archivo "index.html" en donde se deberán agregar los estilos para cada ID por separado.
- Esta separación de archivos y el template inicial del proyecto se da con el objetivo de hacer más fácil el merge de las distintas ramas.

## Features del proyecto

- Navbar con el logo de Myflix, una barra de búsqueda y el nombre e imagen del usuario.
- Contenedor principal con lista de películas agregadas.
- Contenedor con la imagen de la película y calificación.
- Formulario para agregar una nueva película con calificación, nombre e imagen de portada.
- Búsqueda de película por nombre


## Especificaciones

- En la primera posición de la primera fila de películas, siempre debe ubicarse una tarjeta como se detalla en el diseño, que al darle click, se deberá mostrar el modal de formulario para agregar una película.
- En el modal de formulario, se debe agregar una película cuando se presione el botón de "Add" y se debe cerrar el modal sin agregar nada al presionar "Cancel".
- Al dar click en el botón de "Add", en el modal de formulario, se debe validar que el rating, name e imagen hayan sido ingresados. Si alguno de los campos no fue ingresado, se debe mostrar un alert al usuario, indicando este problema.
- La película que se agregue, debe posicionarse en la primera posición de la lista de películas pero después del botón de agregar nueva película.
- Se debe permitir la búsqueda de películas por su nombre exacto.
- Cuando se busque una película y se encuentre una o varias coincidencias, se deberán mostrar en la lista de películas, solo las que coincidan con la búsqueda.
- Si en la búsqueda no se encuentra ninguna coincidencia, no se mostrará película alguna.
- Recuerda que la tarjeta para agregar nuevas películas, siempre debe estar en la primera posición de la primera fila de películas, incluso si se está realizando una búsqueda.
- Para mostrar todas las películas nuevamente, después de hacer una búsqueda, se debe dar click en el botón de buscar con el texto vacío.


## Modelo

Para realizar este trabajo deberás utilizar el concepto de objeto en Javascript para almacenar la información de cada película. El objeto deberá tener la siguiente forma. 

Objeto "movie":

```sh
{
    rating: number,
    name: string,
    image: string
}
```

Para la imagen local seleccionada para una nueva película, deberás utilizar el siguiente formato de ejemplo:
```sh
<img src="file:///C:/Users/username/Documents/movie.jpg" alt="Movie">
```

Para tener la lista de películas con el objeto visto anteriormente, puedes usar el siguiente ejemplo:

```sh
let movies = [
    {
        rating: 2,
        name: "El Titanic",
        image: "file:///C:/Users/username/Documents/titanic.jpg"
    },
    {
        rating: 3,
        name: "Interstellar",
        image: "file:///C:/Users/username/Documents/interstellar.jpg"
    }
]
```


# Haz un excelente trabajo. Tu puedes!
