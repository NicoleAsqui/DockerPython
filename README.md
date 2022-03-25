# DockerPython
#Construir imagen
docker build -t imagenproyecto .

#Ejecutar imagen como un contenedor 

docker run -dp 3000:3000 getting-started          
b34f72442160abd80b7e28de041e0e91a12fc41c6b4e185603ca43cfa7e69144 

Para publicar un puerto para nuestro contenedor, usaremos --publish 
docker run --publish 8080:8080 getting-started 
