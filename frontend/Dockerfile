# Usa una imagen base con Node.js
FROM node:18-alpine

# Define el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia los archivos package.json y package-lock.json (se asume que están en frontend)
COPY package*.json ./

# Instala las dependencias de la aplicación
RUN npm install

# Copia el contenido de la carpeta frontend a /app dentro del contenedor
COPY ./ /app/  

# Expone el puerto que usa la app (puede ser 80 si es una app de React)
EXPOSE 80

# Ejecuta la aplicación
CMD ["npm", "start"]
