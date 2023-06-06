Desarrollo de la guía específica para python ofrecida en Docker docs. 

Link: https://docs.docker.com/language/python/

Creación de app flask conectada con una BD MySQL. Para lo que se utilizó un Dockerfile indicando que la aplicación
se desarrolló en Python 3.11.33, para la que debe instalar las dependencias que se encuentran en el archivo
requirements.txt.

Luego en el docker-compose creamos e iniciamos los servicios necesarios como volumes para la app.py y la BD MySQL.

El resultado fueron dos imágenes diferentes, una para la app y otra para la base de datos conectadas mediante el
manejo de networks que ofrece docker mediante docker-compose. 