# usoGIT
comandos de uso de GIT
aqui pondremos los comandos de GIT
que nbos ayudaran a subir el material

--------------

Calvo y Cobos
Tesis
Uso de GIT
Es un controlador de versiones, lo bueno es q GIT es solo local

Git Hub este recien es para subir a la web

Tutorial de git
youtube
veo version desde terminal:
git version
registro usuario en git (ojo es local)
git config --global user.name "juliano"
veo el usuario registrado (local)
git config --global user.name
registro correo existente en github
git config --global user.email "tesiscalvocobos@gmail.com"
comenzar a trabajar con git en la carpeta
git init
git crea una carpeta oculta (repositorio) en tu ubicacion
creo primer repositorio
git add .
guardo repositorio con mensaje
git commit -m "version 1"
ver los commit o versiones
git log --oneline
guardar nueva version
git add .
git commit -m "version 2"
Una vez creado un repositorio en GitHUB
https://github.com/calvocobos/usoGIT.git

comantos de terminal para vincular con la nube y subir
git remote add origin https://github.com/calvocobos/usoGIT.git
git branch -M main
git push -u origin main
Pasos para subir a partir de ahora
ya no tengo q vincular ya q esta vinculado
creo respaldo
git add .
guardo con mensaje
git commit -m "version 3"
veo mis versiones
git log --oneline
subo a la nuve
git push
