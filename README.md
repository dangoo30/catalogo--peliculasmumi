# MumiPelis: catálogo interactivo de películas

Laboratorio de Diseño Web Aplicación estilo Netflix hecha con React + Vite

## Qué hace

- Muestra un catálogo de 12 películas con póster, título, género, año, calificación y descripción.
- Busca por título mientras se escribe.
- Filtra por género, año, calificación mínima y solo favoritas. Los filtros se combinan con el buscador.
- Abre el detalle de una película en un panel lateral y permite cerrarlo.
- Permite guardar y quitar favoritas, y verlas en su propia sección.
- Permite calificar cada película de 1 a 5 estrellas.
- Muestra un mensaje cuando no hay resultados.

## Componentes

```
App
├── Header
│   └── SearchBar
├── Filters
├── Favorites
├── MovieList
│   └── MovieCard
│       ├── Poster
│       └── StarRating
└── MovieDetail
```

Cada componente está en `src/components/` y los datos en `src/data/movies.js`. El estado compartido está en `App.jsx` y se pasa por props. Las favoritas se guardan solo con sus IDs.

## Instalación y ejecución

Se necesita Node.js 18 o superior.

```bash
git clone <URL-DEL-REPOSITORIO>
cd catalogo-peliculas
npm install
npm run dev
```

Abrir en el navegador la dirección que aparece en la terminal (normalmente http://localhost:5173).

## Aplicación publicada

profe te envio cap aparte 

## Autor

Danna Stephanía Gonzalez Garcia