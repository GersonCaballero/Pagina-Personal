Comandos para crear y ejecutar la imagen de docker
sudo docker build -t "Nombre" .
sudo docker run -it -p 8080:80  --rm --name pagina-running-a-app "Nombre del contenedor"

SE LE PUEDE DEFINIR CUALQUIER NOMBRE Y ESTA DEFINIDO EN EL PUERTO 8080 
EN EL DOCKERFILE

Ejemplo:
sudo docker build -t pagina .
sudo docker run -it -p 8080:80  --rm --name pagina-running-a-app pagina

URL al que se debe ingresar
http://127.0.0.1:8080/