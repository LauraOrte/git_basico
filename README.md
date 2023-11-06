# GIT BÁSICO

1 - Crear .gitignore y README.md 

2 - Iniciar el proyecto:
git init 

3 - Configuración 
git config [--global] user.name 
git config [--global] user.email
git config --global core.autocrlf true (en Mac: input)
git config --global core.editor “code --wait” 

4 - Información del estado
git status

5 - Pasar al STAGE  
git add .gitignore README.md
git add . (para que te suba todo)

6 - Pasar al commit (versión 1)
git commit -m "README hasta el punto 5"
git commit -am "README hasta el punto 6" (solo para los ficheros con M, actualiza todos)

