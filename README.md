# Proyecto de Conexión entre Frontend y Backend con Spring Boot y API REST
App para gestionar un catálogo de películas con un backend en Spring Boot (API REST) y un frontend sencillo en HTML, CSS y JS. Permite hacer un CRUD (Crear, Leer, Actualizar y Eliminar) de películas. Desarrollado con IntelliJ IDEA para el backend y VS Code para el frontend.

## Descripción del Proyecto

Este proyecto es una aplicación de gestión de películas que implementa un frontend simple en HTML, CSS y JavaScript, y un backend en Java con Spring Boot. Muestra cómo conectar un frontend con un backend utilizando una API REST para realizar operaciones CRUD (Crear, Leer, Actualizar y Borrar) sobre una lista de películas.

Desarrollado siguiendo el tutorial "Conexión entre Frontend y Backend con Spring Boot y una API REST", utilicé IntelliJ IDEA para el backend y Visual Studio Code (VSC) para el frontend.

## Estructura del Proyecto

### Backend (Carpeta Peliculas)

- **Lenguaje:** Java
- **Framework:** Spring Boot
- **IDE:** IntelliJ IDEA

**Endpoints del API REST:**

- `GET /api/peliculas`: Obtiene todas las películas.
- `GET /api/pelicula/{id}`: Obtiene una película por ID.
- `POST /api/peliculas`: Crea una nueva película.
- `PUT /api/peliculas`: Actualiza una película existente.
- `DELETE /api/pelicula/{id}`: Elimina una película.

### Frontend (Archivos HTML, CSS y JS)

- **Lenguaje:** HTML5, CSS3, JavaScript
- **IDE:** Visual Studio Code (VSC)

## Funcionalidad

- **Registro de Películas:** Añadir películas con título, autor y género.
- **Listado de Películas:** Mostrar todas las películas con opciones de editar y eliminar.
- **Edición de Películas:** Modificar datos de películas existentes.
- **Eliminación de Películas:** Borrar películas de la base de datos.

