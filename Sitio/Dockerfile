# Utiliza una imagen base de Nginx desde Docker Hub
FROM nginx:alpine

# Elimina el archivo de configuración predeterminado de Nginx
RUN rm -rf /usr/share/nginx/html/*

# Copia los archivos del sitio web al directorio predeterminado de Nginx
COPY sitio /usr/share/nginx/html

# Exponer el puerto 80 para que el tráfico web pueda entrar al contenedor
EXPOSE 80

# Comando para iniciar Nginx cuando se inicie el contenedor
CMD ["nginx", "-g", "daemon off;"]




