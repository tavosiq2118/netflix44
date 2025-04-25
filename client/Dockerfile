# Usa una imagen de Node oficial
FROM node:18

# Crea el directorio de trabajo
WORKDIR /app

# Copia los archivos
COPY . .

# Instala dependencias
RUN npm install

# Expone el puerto
EXPOSE 5000

# Comando para ejecutar el servidor
CMD ["npm", "run", "dev"]
