# LiterAlura

## Descripción

LiterAlura es una aplicación Java que permite gestionar libros y autores utilizando JPA (Java Persistence API) con Hibernate y una base de datos PostgreSQL. La aplicación ofrece diversas funcionalidades para buscar y listar libros y autores, así como obtener estadísticas y datos curiosos.

## Funcionalidades

1. **Buscar libro por título y/o autor (y agregar a base propia)**
2. **Buscar por nombre Autor en el repositorio**
3. **Listar libros registrados**
4. **Listar autores registrados**
5. **Listar autores vivos en un determinado año**
6. **Listar libros por idioma**
7. **Estadísticas basadas en API**
8. **Estadísticas basadas en repositorio**
9. **Datos curiosos con años**

## Estructura del Proyecto

El proyecto está estructurado de la siguiente manera:

- **Modelos**: Definición de las entidades `Autor` y `Libro`.
- **Repositorios**: Interfaces que definen los métodos de acceso a la base de datos para las entidades `Autor` y `Libro`.
- **Servicios**: Clase `LibroService` que proporciona métodos para la búsqueda de libros en una API externa.
- **Principal**: Clase `Principal` que contiene el método `main` y la lógica de la aplicación.

## Uso

Al ejecutar la aplicación, se mostrará un menú en la consola.

