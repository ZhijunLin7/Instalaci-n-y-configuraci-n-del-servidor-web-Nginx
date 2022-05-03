# Instalacion y configuracion de servidor nginx.
## Corona_party y Ant_colony

Mi sistema operativo es Window 10 por eso he descargado nginx para weindow en siguiente link: http://nginx.org/en/download.html
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.1.png)

Luego de tenerlo descargado aparece siguientes archivos y el .exe.
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.2.png)

Antes de todo creare dos archivos llamado webconf donde se guardara los configuraciones y el otro se llamara web donde se guarda los proyectos.
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.3.png)

Ahora vamos a la capeta conf y editamos el nginx.conf le añadimos include ../webconf/*.conf para poder añadir otros webs.
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.4.png)

Desde web one html page challenge elegi dos proyecto corona_party y ant_colony lo colocare en el archivo web.
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.5.png)

Ahora ire al archivo webconf para crear dos documento.conf para configurar el dominio y el direccion del proyecto.
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.6.png)
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.7.png)

Luego buscamos un documento llamado hosts y asignamos los nombre de server en nuestro ip.
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.8.png)

Finalmente iniciamos el nginx y ver el resultado indroduciendo el domini asignado en el navegador.
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.9.png)
![](https://github.com/ZhijunLin7/Instalaci-n-y-configuraci-n-del-servidor-web-Nginx/blob/main/Camera%20Roll/1.10.png)
