<h4 align="center">
  🎓 Alura + ONE
</h4>

<h1 align="center">
  🗣️ Foro Hub
</h1>

<p align="center">
  Este documento proporciona una visión detallada del desarrollo y la documentación del proyecto Foro Hub, parte del curso de API REST con Spring Boot del programa Alura + ONE.
</p>

## 📝 Descripción del Proyecto

El Foro Hub es una API REST desarrollada con Spring Boot que permite gestionar tópicos dentro de un foro. La API permite a los usuarios autenticados crear, listar, actualizar y eliminar tópicos. Los datos se almacenan en una base de datos, y la autenticación se maneja mediante tokens JWT para asegurar el acceso y la integridad de los datos.

## 📋 Funcionalidades

- **Listar Tópicos**: Obtén una lista de todos los tópicos creados en el foro.
- **Crear Tópico**: Permite a los usuarios autenticados crear nuevos tópicos proporcionando detalles como el ID de usuario, el mensaje, el nombre del curso y el título del tópico.
- **Actualizar Tópico**: Modifica los detalles de un tópico existente.
- **Eliminar Tópico**: Elimina un tópico específico del foro.
- **Autenticación**: Utiliza JWT para autenticar a los usuarios antes de permitir operaciones de creación, actualización o eliminación.
- **Documentación de API**: Todos los endpoints están documentados para facilitar la integración y uso.

## 📁 Estructura del Proyecto

- **`src/main/java/com/thiagov2a/forohub`**: Contiene el código fuente de la API, dividido en:
  - **`controller`**: Controladores REST que manejan las solicitudes HTTP.
  - **`domain`**: Modelos de datos y servicios relacionados.
  - **`infra`**: Implementaciones de acceso a datos y configuración adicional.
- **`src/main/resources`**: Archivos de configuración, incluyendo:
  - **`application.properties`**: Configuración de la base de datos y propiedades de la aplicación.
- **`pom.xml`**: Archivo de configuración de Maven que gestiona las dependencias del proyecto.

## 🚀 Cómo Ejecutar el Proyecto

1. **Clonar el Repositorio**: `git clone https://github.com/thiagov2a/challenge-api-rest-alura-one.git`
2. **Navegar al Directorio**: `cd api-rest-alura-one`
3. **Configurar la Base de Datos**: Asegúrate de que MySQL esté instalado y corriendo, y configura la base de datos según las propiedades en `src/main/resources/application.properties`.
4. **Ejecutar el Proyecto**: Utiliza un IDE compatible (como IntelliJ IDEA o Eclipse) para compilar y ejecutar la aplicación. Verifica que las configuraciones en `application.properties` estén correctas.

## 🛠 Tecnologías Utilizadas

- **Java**: 💻 Lenguaje de programación principal.
- **Spring Boot**: 🚀 Framework para construir la API REST.
- **Maven**: 📦 Sistema de gestión de proyectos y dependencias.
- **MySQL**: 🗄️ Sistema de gestión de bases de datos.
- **JWT**: 🔐 Mecanismo de autenticación basado en tokens.

## 🔧 Pruebas

Para probar la API REST, puedes utilizar herramientas como [Insomnia](https://insomnia.rest) o [Postman](https://www.postman.com). Asegúrate de autenticarte utilizando un token JWT válido para realizar operaciones que requieran autenticación, como crear, actualizar o eliminar tópicos.

<p align="center">
  Alura + ONE | Foro Hub
</p>
