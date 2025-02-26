# Principales comandos de Git.
#### Configuración inicial:
 + configurar el nombre de usuario y email:

   > **git config --global user.name "TuNombre"**

   >**git config --global user.email "TuEmail"**
   

# Comandos de trabajo con archivos.
 + Ver el estado de los archivos:
   >**git status**
 + Añadir archivos al área de preparacion (standing area)
   >**git add archivo.txt**
 + Para añadir todos los archivos:
   >**git add .**
 + Hacer un commit:
   >**git commit -m "my commit"**
 + Ver el historial de commits:
   >**git log**


# Trabajar con ramas (branches).
 + Crear una nueva rama:
   >**git branch nombre de la rama**
 + Cambiar a una rama existente:
   >**git checkout nombre de la rama**
 + Crear y cambiar a una nueva rama:
   >**git checkout -b nombre-de-la-nueva-rama**


# Fusionar ramas (merge)
 + Fucionar una rama en la rama actual:
   >**git merge nombre-de-la-rama**


# Trabajar con repositorios remotos.
 + Agregar un repositorio remoto:
   >**git remote add origin https://url-del-repositorio.git**
 + Ver los repositorios remotos:
   >**git remote -v**
 + Subir los cambios al repositorio remoto:
   >**git push**
 + Bajar los cambios del repositorio remoto al local:
   >**git pull**


# Sincronización de repositorios.
  + Clonar un repositorio remoto:
    >**git clone https://url-del-repositorio.git**


# Comandos útiles:
 + Eliminar un archivo del repositorio y del sistema de archivos:
   >**git rm archivo.txt**


# Comandos de ayuda.
 + Ver documentación sobre los comandos git:
   >**git --help**

  
   

