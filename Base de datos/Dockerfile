# Usamos la imagen oficial de MySQL
FROM mysql:8.0

# Configura variables de entorno
ENV MYSQL_ROOT_PASSWORD=12345
ENV MYSQL_DATABASE=test
ENV MYSQL_USER=user
ENV MYSQL_PASSWORD=password

# Copia script inicial si querés
COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 3306