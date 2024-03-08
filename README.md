**Proyecto DOCKER_2ºParte  2ºTRIMESTRE SREI**

Creación mediante mediante Docker de un contenedor DNS y al menos un contenedor que actuará como servidor (web, mysql, ssh,...) 
Se configurará la red, volúmenes y scripts necesarios para ponerlos en marcha.

Instalamos Docker en la máquina virtual

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/847a8e3c-8a20-4e8e-a991-450b998c5674)

Comprobamos que el servicio esté en funcionamiento:

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/dec8c444-5a9c-430b-95ea-03b29773acd6)

Verificamos que Docker se ha instalado correctamente, ejecutamos el siguiente comando:

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/da195a75-8887-430d-b6b4-699353563ec9)

Descargamos la imagen de Apache

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/b81c86b1-788e-45b4-87e0-fc26bbb4ed66)


Creamos el archivo de configuración para el servidor DNS

Primero se crea un directorio donde almacenaremos los archivos de configuración del servidor DNS:

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/dd123aa8-15fd-4bc4-8cf0-b8ca06a5fab3)

Luego, dentro de este directorio,creamos los archivos de configuración para el servidor DNS, como named.conf y las zonas de DNS.

Creamos y ejecutamos un contenedor de DNS:

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/abc3d841-23b1-4a1a-a574-6f1236541855)

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/ed1f40ef-fbf4-4504-9fbf-386575409bfb)


![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/37a079ca-dff0-44e1-aee2-3d641db824eb)

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/ecc8e6a5-4be4-4909-99e1-799c9ca97b17)

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/09b72f42-db75-49aa-b1de-22b62d619414)

Hacemos comprobación:

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/13761b17-dfba-4287-8e3e-a4bb53b2a8ae)

Instalamos paquetes para poder descargar a través de https.

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/c686512f-9a79-4df0-b208-6d96752117b5)

Ponemos una una clave privada

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/14ae34e2-7e41-44f6-b6a8-c0a4a1ce07ce)

Creamos un repositorio 

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/97e5ebf7-62e0-408d-99b0-227c98360fbd)


              CREAMOS UNA RED PARA USAR LOS DOS CONTENEDORES

![image](https://github.com/AngelaMorales-8/Proyecto-DOCKER_SRI/assets/122454505/83fb1966-b1ad-421f-a11d-1094046397c4)



