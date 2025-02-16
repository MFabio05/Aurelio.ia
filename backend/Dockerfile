# Usar una imagen oficial de Node.js
FROM node:18

# Definir el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copiar package.json y package-lock.json para instalar dependencias
COPY package*.json ./

# Instalar dependencias de Node.js
RUN npm install

# Copiar el código fuente de la carpeta src al contenedor
COPY . ./src


# Exponer el puerto de la API
EXPOSE 3000

# Comando para iniciar el servidor
CMD ["npm", "start"]
