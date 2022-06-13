# Instalacion-y-configuraci-n-del-servidor-web-Nginx-Virtual-Hosts

- ![1](https://user-images.githubusercontent.com/72273897/167214738-b37a2158-46d1-43f8-90ff-fa413cd14b6f.PNG).

1. Empezaremos actualizando los repositorios con un #sudo apt-get update y posteriormente realizamos un sudo apt-get install nginx.

- ![2](https://user-images.githubusercontent.com/72273897/167214742-aa2c523e-d485-42c9-a82d-cae012d2f6f8.PNG).

- ![3](https://user-images.githubusercontent.com/72273897/167214752-d8c3afef-ec3e-4b07-854c-a9dd301c5a65.PNG).
- ![image](https://user-images.githubusercontent.com/72273897/167215941-e27c679a-ff18-4701-94e3-ff7d9cf677e7.png).
- ![image](https://user-images.githubusercontent.com/72273897/167216123-5e04028a-d166-4cb8-a33f-914a92432835.png).

2. A continuación nos iremos al directorio "sites-available" mediante la ruta /etc/nginx/sites-available para poder ejecutar el comando cp dos veces, cada uno de los nombres definidos en este.

![image](https://user-images.githubusercontent.com/72273897/167216687-ad3a95d5-82da-4ebc-80a0-45c5c769e15e.png).

3. Aqui tendremps que hacer el siguiente nano en cada archivo copiado para editarlos y eliminar el server dafault en el puerto 80, cambiar la ruta de root de /var/www/html a /var/www/abril1 y /var/www/abril2 y por ultimo agregar el dominio completo detras del server_name.

- ![image](https://user-images.githubusercontent.com/72273897/167217114-fb85aa77-d96d-4093-88f0-c933196b1187.png).

- ![image](https://user-images.githubusercontent.com/72273897/167217183-92b13bcd-ba31-484f-9ca0-6929b10e50ce.png).
- ![image](https://user-images.githubusercontent.com/72273897/167218171-ca2aa8bc-d4b4-47e5-adee-20bc9d39d88f.png).
- ![image](https://user-images.githubusercontent.com/72273897/167218866-9e035abd-b8da-40bc-8395-b82058042e05.png).
- ![image](https://user-images.githubusercontent.com/72273897/167218928-0ec6e363-7299-4c89-82a1-6071ca1f10ef.png).
- ![image](https://user-images.githubusercontent.com/72273897/167219205-e989e5fc-780b-4ba4-a95d-64e1842baf2d.png).
- ![image](https://user-images.githubusercontent.com/72273897/167219508-ec48e453-4b7c-4808-86c1-9dd9526061e7.png).

4. Aqui creamos elaces dirigiendote a la ruta /etc/nginx/sites-enable y utilizar el comando ln -s para crear los enlaces.

- ![image](https://user-images.githubusercontent.com/72273897/167219570-1c2f1354-1060-4830-ab95-8d0cbeadf1a5.png).
- ![image](https://user-images.githubusercontent.com/72273897/167219950-e40c0839-84ce-45fb-a21a-f36044ce44b5.png).
- ![image](https://user-images.githubusercontent.com/72273897/167220330-57c1ab7b-02b8-4855-af66-8805f366049e.png).
- ![image](https://user-images.githubusercontent.com/72273897/167220648-ca4f73b3-c055-49c4-b6d6-5c430ecf5e55.png).
- ![image](https://user-images.githubusercontent.com/72273897/167220615-4fed9c50-f7ae-4037-957f-8d4aa856c365.png).
- ![image](https://user-images.githubusercontent.com/72273897/167221048-b39b5f41-076e-4689-91c2-4e9fde161ae4.png).

5.Ejemplos Finales , visualizados.

- ![image](https://user-images.githubusercontent.com/72273897/167220934-7c535414-de26-4d16-bed8-58ab33b0cfc9.png).
- ![image](https://user-images.githubusercontent.com/72273897/167221006-0a299971-3d76-4ff5-9a66-6ce8aebc9b3d.png).
