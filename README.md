# Proyecto de Conexión entre Frontend y Backend con Spring Boot y API REST
App para gestionar un catálogo de películas con un backend en Spring Boot (API REST) y un frontend sencillo en HTML, CSS y JS. Permite hacer un CRUD (Crear, Leer, Actualizar y Eliminar) de películas. Desarrollado con IntelliJ IDEA para el backend y VS Code para el frontend.

## Descripción del Proyecto

Este proyecto es una aplicación de gestión de películas que implementa un frontend simple en HTML, CSS y JavaScript, y un backend en Java con Spring Boot. Muestra cómo conectar un frontend con un backend utilizando una API REST para realizar operaciones CRUD (Crear, Leer, Actualizar y Borrar) sobre una lista de películas.

## Lo que Aprendí

En este proyecto, he tenido la oportunidad de profundizar en el desarrollo con **Java 21** y en la creación de **microservicios** utilizando **Spring Boot**. A lo largo del desarrollo, aprendí a construir una API REST que permite realizar operaciones CRUD (Crear, Leer, Actualizar y Borrar) sobre una base de datos de películas. 

### Algunos de los conceptos clave que aprendí incluyen:

- **Java 21:** Familiarizarme con las nuevas características de Java 21 me ha permitido mejorar mi comprensión del lenguaje y sus capacidades modernas.
- **Spring Boot:** Aprendí a configurar aplicaciones Spring Boot, lo que facilita la creación de microservicios eficientes y escalables. 
- **API REST:** Comprendí cómo diseñar y construir APIs RESTful, lo que es fundamental para la comunicación entre el frontend y el backend en arquitecturas modernas.
- **Microservicios:** He explorado la arquitectura de microservicios, lo que me ha proporcionado una visión clara de cómo dividir una aplicación en servicios independientes que pueden comunicarse entre sí.
- **Manejo de Bases de Datos:** Aprendí a interactuar con bases de datos (en este caso, H2) a través de JPA, lo que facilita la persistencia de datos.

Este proyecto no solo ha sido una excelente manera de aplicar mis conocimientos, sino que también ha reforzado mi interés en seguir aprendiendo sobre Java, Spring Boot y el desarrollo de microservicios. Estoy emocionado por los futuros proyectos y por continuar expandiendo mis habilidades en este campo.


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

