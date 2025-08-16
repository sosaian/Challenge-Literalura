# Literalura: Aplicación para Buscar y Registrar Libros

## Requisitos Básicos

- **Buscar libro por título**  
    - El usuario ingresa el nombre del libro.  
    - La aplicación busca la información del libro en la API Gutendex y lo registra en la base de datos.  
    - Mostrar un mensaje si el libro no se encuentra en la API.

- **Listar libros registrados en la base de datos**  
    - Mostrar todos los libros almacenados en la base de datos.

- **Listar autores registrados**  
    - Mostrar todos los autores almacenados en la base de datos.

- **Listar autores vivos en un determinado año**  
    - El usuario ingresa un año.  
    - Mostrar los autores que estaban vivos en ese año.

- **Listar libros por idioma**  
    - El usuario ingresa el código de idioma (ES, EN, FR, PT).  
    - Mostrar los libros en ese idioma.

- **Manejo de errores**  
    - Mostrar un mensaje si el libro no se encuentra en la API.  
    - Evitar insertar el mismo libro más de una vez en la base de datos.

## Configuración Inicial del Proyecto

- Crear un proyecto Maven en Java usando [Spring Initializer](https://start.spring.io).  
- Utilizar la versión más reciente de Spring Boot (sin snapshots ni M3).  
- Utilizar Java 17.

## Añadir las dependencias

- Spring Data JPA  
- PostgreSQL Driver  

## API a Consumir

- [Gutendex](https://gutendex.com) (API para buscar libros)
