# Primer Parcial Lenguaje de Cuarta Generación
Realizar una aplicación Crud, con las funciones: Create, Read y Update, para la administración de usuarios

## 1. Formulario de Crear (Puntos: 1.5)
Tener en cuenta en el formulario de crear, se deberá permitir crear usuarios con la siguiente información:

* Nombres
* Apellidos
* Email
* Password

Nota: El campo contraseña, deberá realizarse mediante el input de tipo "password", y al momento de almacenar en la base de datos, deberá encriptarse en MD5.
Por defecto, al crear un nuevo usuario, este iniciará con el estado Activo

## 2. Formulario de Edición (Puntos: 1.5)
En el formulario de edición se deberá solicitar la siguiente información:

* Nombres
* Apellidos
* Email
* Password
* Estado

Nota: El campo password, deberá venir vacio, y cuando se envie a guardar la información, se debe validar si la contraseá viene vacia, no se actualiza el campo, y si por el contrario esta lleno, se aplica la nueva contraseña encriptada en md5

## 3. Lectura de información (Puntos: 2)
En la tabla se deberá mostrar la siguiente información:

* ID
* Nombres
* Apellidos
* Email
* Estado
* Acciones

Nota: La acción Activar/Inactivar, es una acción rapida que activa o inactiva un usuario sin necesidad de ir a actualizar la información mediante el formulario de edición


Una vez finalizado el proyecto, se deberá subir a un repositorio de git, con el nombre: LG4-Parcial 1, incluyendo el código y la base de datos

Nota: Podra utilizar este proyecto como base para iniciar el parcial, recuerde aplicar todos el conocimiento aprendido durante la clase

Plazo máximo de entrega el día 16 de Marzo de 2020 hasta las 10:30 pm