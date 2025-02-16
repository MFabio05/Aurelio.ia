# Proyecto Aurelio

Este proyecto es un asistente virtual basado en IA. Para iniciar el proyecto, sigue los siguientes pasos:

## Configuración del Backend

1. Clona el repositorio.

   ```terminal
   git clone https://github.com/tuusuario/aurelio.ia.git
   cd aurelio.ia
   ```

2. Navega a la carpeta `backend`.

   ```terminal
   cd backend
   ```

3. Instala las dependencias con el siguiente comando:

   ```terminal
   npm install
   ```

4. Copia el archivo `.env.example` a `.env`:

   ```terminal
   cp .env.example .env
   ```

5. Abre el archivo `.env` y configura las variables necesarias, como el puerto de la aplicación y las credenciales de la base de datos:

   ```env
   PORT=3000
   DB_HOST=localhost
   DB_PORT=3306
   DB_USER=tu_usuario
   DB_PASSWORD=tu_contraseña
   DB_NAME=tu_base_de_datos
   ```

6. Ejecuta el servidor con:

   ```terminal
   npm start
   ```

## Configuración del Frontend

1. Navega a la carpeta `frontend`.

   ```terminal
   cd ../frontend
   ```

2. Instala las dependencias con el siguiente comando:

   ```terminal
   npm install
   ```

3. Copia el archivo `.env.example` a `.env`:

   ```terminal
   cp .env.example .env
   ```

4. Abre el archivo `.env` y configura las variables necesarias, como la URL de la API:

   ```terminal
   REACT_APP_API_URL=http://localhost:3000
   ```

5. Ejecuta el servidor con:

   ```terminal
   npm start
   ```

## Conexión a la base de datos

Si estás utilizando MySQL, asegúrate de tener una base de datos configurada en tu entorno local. Para ello, crea una base de datos llamada `aurelio_db` (o ajusta el nombre en el archivo `.env` de acuerdo con tu configuración).

Puedes crear la base de datos ejecutando el siguiente comando en MySQL:

```sql
CREATE DATABASE aurelio_db;
```
