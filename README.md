Los contenedores son una forma de virtualización del sistema operativo. Un solo contenedor se puede usar para ejecutar cualquier cosa, desde un microservicio o un proceso de software a una aplicación de mayor tamaño. Dentro de un contenedor se encuentran todos los ejecutables


![image](https://user-images.githubusercontent.com/91167211/197315447-1ab0d76b-3d98-43f2-904a-f0cb5068db4a.png)




Play with Docker (PWD) es un proyecto hackeado por Marcos Liljedhal y Jonathan Leibiusky y patrocinado por Docker Inc.

PWD es un patio de recreo de Docker que permite a los usuarios ejecutar comandos Docker en cuestión de segundos. Proporciona la experiencia de tener una máquina virtual Alpine Linux gratuita en el navegador, donde se pueden construir y ejecutar contenedores Docker e incluso crear clusters en el modo Docker Swarm . Bajo el capó, se utiliza Docker-in-Docker (DinD) para dar el efecto de múltiples VM/PC. Además de la zona de juego, PWD también incluye un sitio de formación compuesto por un gran conjunto de pruebas y laboratorios Docker, desde el nivel principiante hasta el avanzado, disponible en training.play-with-docker.com .

--- Para crea un servidor se inserta el siguiente comando
--- docker run --name serverweb -p 80:80 -d nginx

![image](https://user-images.githubusercontent.com/91167211/197422234-faa1664b-95f2-4a8d-bcf6-799b21a05e4e.png)


--- Para verificar si esta corriendo o esta correctamente instalado utilizar el comando : docker ps

![image](https://user-images.githubusercontent.com/91167211/197422378-926725da-e654-4b50-b502-10223889add9.png)

--- Para observar el puerto colocamos el #80

![image](https://user-images.githubusercontent.com/91167211/197422525-536896b6-9540-4fae-b716-c0a9c5e89a71.png)

------ Comando Básico de Docker ------

>> docker run: correr un contenedor

>> docker ps: Listan los contenedores que están corriendo

>> (-- name serverweb): Es para colocar un nombre y sirve para identificar el docker y donde está corriendo

>> 80:80: Maquina anfitriona

>> -d: Permite seguir ocupando la línea de comandos, si usamos el proceso pasa a segundo plano


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------


                                                                   Clase #2


![image](https://user-images.githubusercontent.com/91167211/197423040-d54e479a-7eac-47ef-9d88-b4a5ce7a2b81.png)


