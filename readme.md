#Instrucciones de GIT

## Instrucciones esenciales
### Configuración de git
git config --global init.defaultBranch main <- rama por defecto>


### Iniciar el repositorio
git init <- iniciar el repositorio
### Añadir ficheros a la fase Add
git add readme.md
git add *.html
git add .
git add --all 
### Fichero para ignorar lo que no nos interese
.gitignore 

### Subir a la fase "commit" = validación
git commit -m "Mensaje explicativo"
### Si modificamos un fichero va a parar a la fase Modified
git restore nombre_fichero <- revierte los cambios (como un CTRL + Z)>
git add . <- para volver a la fase Add>
git commit -m "Otro mensaje" <- para volver a la fase commit>
git commit -a "mensaje" <-salta de golpe a la fase commit de nuevo>
git commit -a -m "actualizada instrucción"
## Instrucciones de control
git status
git log
git log --oneline <- historial de commits resumido>

## Instrucciones para subir ficheros a un repositorio en la nube.
git remote add origin https://github.com/Sk8ener/intrucciones-git-github-2025.git

## Instrucciones oara las ramas 
git branch <- obtener las ramas del proyecto>
git branch -M main <- cambiar el nombre a la rama actual (pasará a ser Main)>