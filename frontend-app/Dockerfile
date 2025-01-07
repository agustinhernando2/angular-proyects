FROM node:12

# Establecer el directorio de trabajo
WORKDIR /usr/src/app

# Copiar archivos del proyecto
COPY . /usr/src/app/

# Instalar Angular CLI 8
RUN npm install -g @angular/cli@8

# Exponer puerto de desarrollo
EXPOSE 4200

# Comando para iniciar la aplicación
CMD ["npm", "start"]
