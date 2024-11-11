Juego de Adivinanza de Números
¡Bienvenido al Juego de Adivinanza de Números! Este es un juego simple creado con Node.js y JavaScript donde el usuario debe adivinar un número secreto entre 1 y 10 en un máximo de 5 intentos. El juego proporciona pistas de si el número es muy bajo o muy alto.

Descripción
Este proyecto es un juego de consola en el cual el usuario tiene que adivinar un número secreto entre 1 y 10. El jugador tiene 5 intentos para adivinar el número correctamente. Si se quedan sin intentos o adivinan el número, el juego se detiene.

Funcionalidades principales:
Generación aleatoria de un número secreto entre 1 y 10.
5 intentos para adivinar el número.
Retroalimentación en tiempo real sobre si el número es demasiado alto o bajo.
Deshabilita la entrada y el botón después de adivinar el número o quedarse sin intentos.
Tecnologías utilizadas
Node.js: Entorno de ejecución para JavaScript en el servidor.
JavaScript: Lenguaje de programación utilizado para la lógica del juego.
HTML: Para la interfaz de usuario.
CSS: Para el diseño visual de la aplicación.
Docker: Para crear una imagen contenedora que permita ejecutar la aplicación de manera aislada.
Estructura del proyecto
La estructura básica del proyecto es la siguiente:

bash
Copiar código
/mi-juego-adivinanza
│
├── /public
│   └── index.html       # Archivo HTML que contiene la vista del juego.
│
├── /src
│   └── server.js        # Lógica del servidor y configuración de Express.
│
├── Dockerfile           # Configuración para crear la imagen Docker.
├── package.json         # Dependencias del proyecto y scripts de NPM.
└── README.md            # Este archivo README.
Requisitos previos
Asegúrate de tener las siguientes herramientas instaladas en tu máquina:

Node.js: Descargar e instalar Node.js
Docker: Descargar e instalar Docker
Instalación
1. Clonar el repositorio
Primero, clona este repositorio en tu máquina local usando Git:

bash
Copiar código
git clone https://github.com/tu-usuario/mi-juego-adivinanza.git
2. Instalar dependencias
Accede a la carpeta del proyecto y ejecuta el siguiente comando para instalar las dependencias de Node.js:

bash
Copiar código
cd mi-juego-adivinanza
npm install
3. Ejecutar la aplicación en desarrollo
Para ejecutar la aplicación localmente, puedes utilizar el siguiente comando:

bash
Copiar código
npm start
Esto iniciará un servidor en http://localhost:3000 y podrás acceder al juego desde tu navegador.

Docker
1. Construir la imagen de Docker
Asegúrate de tener Docker instalado. Luego, en la raíz del proyecto, ejecuta el siguiente comando para construir la imagen de Docker:

bash
Copiar código
docker build -t mi-juego-adivinanza .
2. Ejecutar la aplicación en Docker
Una vez construida la imagen, puedes ejecutar el contenedor con:

bash
Copiar código
docker run -p 3000:3000 mi-juego-adivinanza
Este comando mapea el puerto 3000 del contenedor al puerto 3000 de tu máquina local, lo que te permitirá acceder al juego en http://localhost:3000.

Uso
Abre tu navegador y ve a http://localhost:3000.
El juego mostrará un campo para introducir un número entre 1 y 10.
Introduce un número y haz clic en "Adivinar".
El juego te dará pistas sobre si el número es muy bajo o muy alto.
Si adivinas el número o te quedas sin intentos, el juego se detendrá.
Contribución
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama para tu característica (git checkout -b feature/mi-nueva-caracteristica).
Realiza tus cambios y haz un commit (git commit -am 'Agregada mi nueva característica').
Haz push a tu rama (git push origin feature/mi-nueva-caracteristica).
Abre un pull request.
Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.