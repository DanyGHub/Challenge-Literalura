# 📚 Literalura

Literalura es una aplicación hecha en Java que permite consultar información de libros a través de la API de [Gutenberg](https://gutendex.com/), guardarlos en una base de datos local (PostgreSQL 17).  

El objetivo principal es combinar el consumo de API y el almacenamiento en bases de datos dentro de un mismo proyecto.


## 🧰 Tecnologías utilizadas
- **Java 17+**
- **API REST:** [Gutendex](https://gutendex.com/)
- **Base de datos:** PostgreSQL 17
- **Librerías externas:**
  - `Gson` para el parseo JSON
  - `PostgreSQL Driver `
  - `Spring Data JPA`


## 🧪 Funcionalidades del Menú
Al ejecutar la aplicación, se muestra un menú interactivo en consola con las siguientes opciones:
- 1- Buscar Libro en el API por Título.
- 2- Listar libros de la Base de Datos.
- 3- Listar Autores de la Base de Datos.
- 4- Listar Autores en un determinado año [estando vivos].
- 5- Listar Libros de la Base de Datos por Idioma.
- 0- Finalizar Programa.

## 🗃️ Base de Datos
Se utiliza **PostgreSQL 17** como almacenamiento local.

### Tabla creada:
- `libros`  
  Contiene: `id`, `titulo`, `lenguajes`, `autores`, `anio_nacimiento`, `anio_muerte`

## ✅ Requisitos para correr el proyecto
- Java 17 o superior  
- IntelliJ IDEA o cualquier IDE con soporte para Maven o Gradle  
- Conexión a internet necesaria para consumir la API de Gutendex 
- Base de datos configurada correctamente  

## 🚀 Cómo ejecutar
  1- Clona el Repositorio.
  2- Abre el proyecto en tu IDE de preferencia.
  3- Asegurate de tener las dependencias necesarias.
  4- Dentro de la Clase LibroDB, cambie las confiduraciones necesarias para hacer la conexión de la API correctamente.
  5- Ejecute el archivo Demo para hacer uso del Proyecto.
