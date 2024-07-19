# MusicAttendance

MusicAttendance es una aplicación móvil diseñada para la gestión de la asistencia y el tiempo de trabajo en instituciones educativas musicales. Esta herramienta permite a los profesores y administradores registrar la entrada y salida, así como pasar lista a los alumnos, centralizando la información en una plataforma accesible.

## Descripción del Proyecto

### Resumen

El proyecto MusicAttendance surge de la necesidad de disponer de herramientas efectivas para el registro y seguimiento de la asistencia de profesores y alumnos en una escuela musical. Considerando la importancia de una gestión adecuada del tiempo y la asistencia para mantener la calidad educativa y organizativa, se ha desarrollado esta aplicación móvil con una interfaz intuitiva y fácil de usar.

### Objetivos

- Registrar la entrada y salida de los profesores.
- Pasar lista para registrar la asistencia de los alumnos.
- Generar informes detallados de las horas trabajadas y las faltas de asistencia.
- Facilitar la gestión de listas de alumnos y la asignación de instrumentos.




### Funcionalidades de la Aplicación

- **Inicio de Sesión**
  - Los usuarios inician sesión con su nombre de usuario y contraseña para acceder a la aplicación.

- **Registro de Cuenta**
  - Para nuevos usuarios, permite registrarse proporcionando datos como correo electrónico, nombre de usuario y contraseña, con validación por correo electrónico.

- **Perfil de Usuario**
  - Pantalla donde los usuarios pueden ver y modificar sus datos personales.

- **Registro de Fichaje**
  - Permite a los usuarios registrar su fichaje seleccionando la hora y el día, indicando si es presencial o remoto, y añadiendo observaciones si es necesario.

- **Registro de Asistencia**
  - Los usuarios pueden seleccionar la lista de alumnos de cada curso para registrar la asistencia a las clases.

- **Registro de Salida**
  - Permite ingresar la hora de salida y realizar modificaciones en los datos de fichaje si es necesario.

- **Historial de Fichajes**
  - Muestra todos los fichajes realizados, permitiendo su visualización y búsqueda por tramos de fecha.

- **Crear Lista de Asistencia**
  - Permite a los usuarios crear una lista de asistencia para cada curso, donde pueden ver a los alumnos y marcar su asistencia durante las clases.


### Funcionalidades futuras

- **Validaciones por Correo Electrónico**
    - Registro: Implementación de validación por correo electrónico al registrarse.
    - Cambio de Contraseña: Validación por correo electrónico para el cambio de contraseña.
- **Gestión de Listas de Alumnos**
    - Modificación de Listas: Permite modificar listas de alumnos existentes.
    - Creación de Alumnos: Crear nuevos perfiles de alumnos.
    - Importación de Alumnos: Enviar un archivo Excel con la información de los alumnos para su importación en la base de datos.
- **Mejora Visual de la Aplicación**
    - Interfaz de Usuario: Diseño moderno y atractivo para facilitar la navegación y el uso intuitivo.
- **Generación de Informes**
    - Horas Trabajadas por los Profesores: Informes detallados de las horas trabajadas.
    - Faltas de Asistencia de los Alumnos: Informes sobre las faltas de asistencia.
- **Funcionalidades de Comunicación**
    - Chat Interno: Comunicación entre profesores.
    - Envío de Partituras: Capacidad para enviar partituras y otros materiales educativos.
- **Gestión de Instrumentos**
    - Almacenamiento de Instrumentos: Información sobre los instrumentos disponibles.
    - Asignación de Instrumentos: Asignación de instrumentos a los alumnos.
- **Rol de Administrador**
    - Gestión de Usuarios: Acceso a las horas de alumnos y profesores, creación y administración de usuarios y listas.
    - Restricciones para Otros Usuarios: Los demás usuarios no tendrán acceso a la creación de listas.
 
## Video demo
[![Demostración del código](https://img.youtube.com/vi/0-n2354l0UY/maxresdefault.jpg
)](https://youtu.be/0-n2354l0UY)



## Tecnologías Utilizadas

- **Backend:** Spring Boot
- **Base de Datos:** MongoDB
- **Despliegue:** AWS EC2
- **Frontend:** React Native y Expo
- **Testing:** Postman para pruebas de la API
- **Diseño:** Figma para la creación de mockups

#   Descarga apk
![Descargar apk](https://github.com/Florida2DAM/pfc-23-24-Borja2001/blob/main/Documentos/QrAPK.jpeg)
  - ## Modo de uso
    -  Descarga la app
    -  Usuario: Borja
    -  Contraseña: 1234

# Instalación del código

### Prerequisitos

- Node.js
- npm
- MongoDB
- Cuenta en AWS (No obligatorio, solo para desplegar en remoto)

### Instalación

1. Clonar el repositorio:
    ```bash
    git clone <https://github.com/Florida2DAM/pfc-23-24-Borja2001.git>
    ```
2. Navegar al directorio del proyecto:
    ```bash
    cd pfc-23-24-Borja2001
    ```
3. Instalar dependencias del frontend:
    ```bash
    cd Registre_UMM
    npm install
    ```
4. Instalar dependencias del backend:
    ```bash
    cd PFC
    mvn install
    ```



### Despliegue en AWS

1. Configurar una instancia EC2 en AWS.
2. Desplegar el backend en la instancia EC2.
3. Configurar MongoDB en AWS o utilizar un servicio de base de datos gestionado.
