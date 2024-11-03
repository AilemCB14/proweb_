# Programación Web Evaluación Nro. 1

*Ailem Cañizalez*. 

**Crear un repositorio en github.**

Inicie sesión en mi cuenta GitHub y cree un repositorio con nombre "proweb_", seleccione que será público y finalmente inicie el repositorio.

![Repositorio](/img_readme/repositorio.PNG)
___

**Crear tres branchs: main, staging y develop**.

Primero cree una carpeta en mi Desktop donde será alojado el código de la página web a realizar, utilizo la terminar "Open Git Bash here" donde indicare con el comando git init que se trata de un nuevo proyecto. 

![Carpeta](/img_readme/carpeta.PNG)
___

Seguido de esto con el comando git branch se ve la lista de branchs actuales, se encuentra predeterminado la branch "main".

![git branch](/img_readme/git%20branch.PNG)
___

Para crear las dos (2) branchs adicionales se usa el comando: **git branch nombre_branch**

![git branch staging](/img_readme/git%20branch%20staging.PNG)

![git branch develop](/img_readme/git%20branch%20develop.PNG)

___

Las ramas creadas estan de forma local en nuestro dispositivo, pero no aparecerán en el repositorio de GitHub online, para que suceda se deben realizar dos comandos: 

1. **git switch nombre_branch** permite cambiar a una de las branchs creada. 
2. Con **git push origin nombre_branch** permite subir al GitHub la branch en la que estamos posicionados. 
3. Ambos pasos se repite para las dos branchs creadas  (develop y staging).  

![git switch y push staging](/img_readme/git%20switch%20y%20push%20staging.PNG)

![git switch y push develop](/img_readme/git%20switch%20y%20push%20develop.PNG)



