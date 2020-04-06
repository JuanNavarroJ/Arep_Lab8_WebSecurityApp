# Aplicación distribuida segura en todos sus frentes

## Desarrollo 

### Http + Ssl = Https

Se creal el certificado.
![clave1](https://user-images.githubusercontent.com/44879884/78603756-4af2ce80-781e-11ea-967d-2752a1aaf5f1.PNG)

El navegador reconoce que no es un certificado valido por una empresa certificada.
![noconfia](https://user-images.githubusercontent.com/44879884/78603763-4cbc9200-781e-11ea-930a-3fdb5358ca20.PNG)

Le decimos que puede confiar en nuestro certificado.
![confie](https://user-images.githubusercontent.com/44879884/78603760-4c23fb80-781e-11ea-961d-a91c454a7741.PNG)

Ahora que el browser confia en el certificado podemos ver el contenido de la pagina.
![yaconfia](https://user-images.githubusercontent.com/44879884/78603764-4cbc9200-781e-11ea-8b37-98086396a8a9.PNG)

Vemos que estamos usando un certificado para conectarnos.
![certificado](https://user-images.githubusercontent.com/44879884/78603765-4d552880-781e-11ea-991d-ac5a1c63c5a9.PNG)

Vemos la informacion de nuestro certificado.
![infocertificado](https://user-images.githubusercontent.com/44879884/78603762-4c23fb80-781e-11ea-9b14-a5e79440f771.PNG)

### Prerequisites

Debemos tener los siguientes programas instalados:
```
- Maven 
- Git
- Navegador web
```

## ¿Como instalar y probar?

Debemos tener un editor java instalado y git, es opcional tener instalado el uso de maven que permitira un mejor control sobre el proyecto.

1. Entramos la terminal del dispositivo y accedemos a la carpeta en la cual queremos guardar el proyecto. 

![1](https://user-images.githubusercontent.com/44879884/75121441-fb878300-5661-11ea-91b5-330ef63613a1.PNG)

2. Usando los comandos de git empezamos con : **$ git clone** https://github.com/JuanNavarroJ/Arep_Lab5_AWS.git e Ingresamos a la carpeta que descargamos desde Github.

![2](https://user-images.githubusercontent.com/44879884/75121443-fc201980-5661-11ea-8f00-3088434e741c.PNG)

3. Usando maven podemos en la linea de comandos compilar y ejecutar el proyecto con el codigo **$ mvn package**

![3a](https://user-images.githubusercontent.com/44879884/75121444-fcb8b000-5661-11ea-978e-c8be43e677fd.PNG)
![3b](https://user-images.githubusercontent.com/44879884/75121445-fcb8b000-5661-11ea-8615-1fabfffed750.PNG)

4. Si deseas conocer a profundidad el funcionamiento del codigo, podemos abrir el proyecto en un editor java.

![4](https://user-images.githubusercontent.com/44879884/75121446-fcb8b000-5661-11ea-89a4-0bddf55da9fe.PNG)

5. Para generar el javadoc ejecutamos el comando **$ mvn javadoc:javadoc**

![5a](https://user-images.githubusercontent.com/44879884/75121448-fe827380-5661-11ea-930d-c116ce286949.PNG)


## Desarrollo

Construido con:

-   [Maven](https://maven.apache.org/)  - Control de dependencias

-	 [CircleCI](https://circleci.com/)  - Despliegue continuo

-	 [Heroku](https://dashboard.heroku.com/apps) - Plataforma Web

## Autor

-   **Juan David Navarro Jimenez**    -  [JuanNavarroJ](https://github.com/JuanNavarroJ)

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](https://github.com/JuanNavarroJ/Arep_Lab8_WebSecurityApp/blob/master/LICENSE.txt) file for details.
