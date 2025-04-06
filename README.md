Gestión de Hábitos

Descripción

Esta aplicación web permite a los usuarios gestionar hábitos diarios, ayudándoles a desarrollar buenos hábitos o deshacer malos hábitos.

Tecnologías

Next.js
Express.js
MongoDB (MongoDB Atlas)
Mongoose
dotenv
cors

Requerimientos

Node.js (v16+)
MongoDB Atlas (Base de datos en la nube)
Postman (Opcional, para probar los endpoints)

Instalación

Clona el repositorio:
git clone https://github.com/ByronMonzon/habitos_aplicacion.git
cd aplicacion_habitos

Instala las dependencias del servidor:

cd server
npm install

Configura las variables de entorno: Crea un archivo .env en la carpeta del servidor con el siguiente contenido:

MONGO_URI=tu_conexion_mongodb_atlas
PORT=3000

Inicia el servidor:

npm start para backend
npm run dev para frontend

Abre el navegador en http://localhost:3000