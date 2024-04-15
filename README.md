
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP(Hypertext Preprocessor):** PHP es un lenguaje de programación de código abierto ampliamente utilizado para el desarrollo de aplicaciones web del lado del servidor. Permite la creación dinámica de contenido web, la interacción con bases de datos y la gestión de sesiones de usuario, entre otras funcionalidades. PHP se ejecuta en el servidor y genera HTML que se envía al navegador del usuario.
- **MySQL:** MySQL es un sistema de gestión de bases de datos relacional (RDBMS) de código abierto. Es ampliamente utilizado en aplicaciones web para almacenar y gestionar datos de manera eficiente. MySQL utiliza el lenguaje SQL (Structured Query Language) para realizar consultas y manipular datos en la base de datos.
- **HTML(Hypertext Markup Language) & CSS(Cascading Style Sheets):** HTML es el lenguaje estándar utilizado para crear y estructurar el contenido de páginas web. Define la estructura y el significado del contenido mediante etiquetas y elementos. CSS, por otro lado, se utiliza para dar estilo y diseño a las páginas web. Permite controlar aspectos como el color, el diseño, la tipografía y el espaciado del contenido HTML.
- **Tailwind CSS:** - **HTML(Hypertext Markup Language) & CSS(Cascading Style Sheets):** HTML es el lenguaje estándar utilizado para crear y estructurar el contenido de páginas web. Define la estructura y el significado del contenido mediante etiquetas y elementos. CSS, por otro lado, se utiliza para dar estilo y diseño a las páginas web. Permite controlar aspectos como el color, el diseño, la tipografía y el espaciado del contenido HTML.Tailwind CSS es un framework de CSS utilitario que facilita el desarrollo rápido y la construcción de interfaces de usuario personalizadas. A diferencia de otros frameworks CSS que utilizan clases predefinidas, Tailwind CSS proporciona una amplia gama de clases utilitarias que se aplican directamente al HTML para estilizar los elementos. Esto ofrece un alto grado de flexibilidad y control sobre el diseño de la interfaz de usuario sin la necesidad de escribir CSS personalizado.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

