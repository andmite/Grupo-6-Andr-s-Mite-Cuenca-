# Grupo 6 Proyecto Guía Práctica de aplicación y experimentación Grupo F

## Descripción

_Implementación de una topología de red Mixta usando la distribución de Mininet._

## Integrantes Grupo F:

Andrés Mite Cuenca

### Procesos para seguir detallados haciendo una implementación de una topología de red usando Mininet.

Antes de continuar debemos saber, ¿Qué es Mininet?

Mininet es un emulador para el despliegue de rede sobre los limitados recursos de un ordenador sencillo simple o máquina virtual.

![Captura 1](https://user-images.githubusercontent.com/86998421/125018397-a1ab1180-e03a-11eb-91fb-b65e179fe30a.JPG)

Una vez instalada la máquina virtual debemos abrir la terminal con el siguiente comando:
```
Start/Accessories/LXTerminal
```

![Captura](https://user-images.githubusercontent.com/86998421/125018652-2433d100-e03b-11eb-9406-00eecd627054.JPG)

Luego de abrir la terminal de Mininet ejecutamos el comando que nos permitirá que se cree una red que nos servirá para que se añadan e inicialicen los controles, aparte de los hosts con los que se trabajará.
```
$sudo mn
```

![Captura 2](https://user-images.githubusercontent.com/86998421/125018765-5e04d780-e03b-11eb-8c69-3050af245189.JPG)

Luego de los comandos aplicados anteriormente ejecutamos el siguiente que nos ayudara a ejecutar el nodo del host2.
```
mininet> net
mininet> xterm h2
```

![Captura 3](https://user-images.githubusercontent.com/86998421/125018940-a3c1a000-e03b-11eb-88b9-19d510dec8bc.JPG)

### Luego que abramos el terminal de comandos del nodo2 accedemos a la siguiente ruta:
```
$:root@mininet-vm:/home/mininet/mininet/examples# 
```
Luego de aplicarlo ejecutamos el archivo:
```
python miniedit.py
```
### Luego seguimos los siguientes comandos para poder acceder:
```
$ root@mininet-vm:~# cd..
$ root@mininet-vm:/# ls
$ root@mininet-vm:/# cd home
$ root@mininet-vm:/home# cd mininet
$ root@mininet-vm:/home/mininet# cd mininet
$ root@mininet-vm:/home/mininet/mininet# cd examples
$ root@mininet-vm:/home/mininet/mininet/examples# ls
```
![Captura 4](https://user-images.githubusercontent.com/86998421/125019116-05820a00-e03c-11eb-8607-8d9422f50f9a.JPG)

Luego de estar en la ruta se ejecuta el siguiente comando:
```
$ root@mininet-vm:/home/mininet/mininet/examples# python miniedit.py
```
Aquí es cuando se nos abrirá la pantalla de Miniedit que es donde haremos la implementación de la red.

Una vez dentro del Miniedit implementamos una red Mixta que consta de un total de 13 dispositivos entre los switches y hosts.

Específicamente consta de:
- 8 terminales Host
- 4 Switchs
- 1 Router

### ![Captura 5](https://user-images.githubusercontent.com/86998421/125019240-411cd400-e03c-11eb-924e-e2c4d82fd90a.JPG)

Se adjunta archivo con la red implematada con el nombre Topologia_Andres_Mite









