# TutorialPasosGIT

# Como crear un repositorio y subirlo desde git a github
 
En esta sección aprederemos como se ejecutan los comando en la consola de git para subir nuestro proyecto al repositorio de github. Es menester tener en cuenta que para realizar estos pasos ya debemos tener instalada de manera correcta git en en nuestro pc.


Paso # 1
Debemos ejecutar la carpeta donde esta el proyecto con click derecho sobre la carpeta y debemos darle a la opcion de "git bush here"

![image](https://user-images.githubusercontent.com/124592267/220134978-66302dba-8928-4c1b-977b-41aae45c710d.png)



Paso # 2 
Se no abrira la consola de comandos de git y ahora para inicializar la subida de nuestro proyecto debemos introducir el siguiente comando

git init

Y debe mostrarnos la siguiente info

![image](https://user-images.githubusercontent.com/124592267/220135977-866c2410-193b-4a29-87ec-197537f5a6e5.png)



Paso # 3
Seguidamente ejecutamos el siguiente comando:

git remote add origin "URL repositorio SSH"

para añadir la url la encontramos en la siguiente parte

![image](https://user-images.githubusercontent.com/124592267/220136537-1eb9ce4d-c0c8-4d7c-b4e8-1ccd417d4576.png)

Le damos enter y deberiamos ver la siguiente informacion

![image](https://user-images.githubusercontent.com/124592267/220136897-2673bf20-9e6c-442a-b39f-be6daef61fcb.png)



Paso # 4
Ahora debemos ejecutar los siguiente comandos que son para verificar que nuestro repositorio no tenga cambios no guardados

git fetch origin main

Y deberia mostrarnos la siguiente info

![image](https://user-images.githubusercontent.com/124592267/220137389-2231a8ed-5145-4672-ba24-c760529f8cd7.png)

Seguidamente debemos ejecutar:

git pull origin main

Y deberia mostrarnos la siguiente info

![image](https://user-images.githubusercontent.com/124592267/220137663-a60e1be9-965a-452f-b2d4-d68db3d0beed.png)



Paso # 5 
Ejecutamos:

git add .

este comando es para agregar todo lo que tengamos en la carpeta a git, y deberia mostrarnos la siguiente info

![image](https://user-images.githubusercontent.com/124592267/220137994-4428a16f-8b05-414b-b71e-07705c1c6d6a.png)



Paso # 6 
Ejecutamos ahora:

git commit -m "Fist Commit"

![image](https://user-images.githubusercontent.com/124592267/220138215-b8601cd5-81dd-4bce-8a10-523c8ee075bf.png)



Paso # 7
 Y finalmente ejecutamos:
 
 git push -u origin main
 
 Y debe aparecernos la siguiente info de que se ha completado y subido todos los archivos con exito.
 
 ![image](https://user-images.githubusercontent.com/124592267/220144149-62ffae1e-e1c4-4991-83c3-02156c7f0462.png)


Eso seria todo, ahora debemos verificar que hayan quedado los archivos en el repositorio de github
