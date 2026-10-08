# Bitacora 2

Nota: bitacora2.md fue creado en C:\Users\quant\Documents\WEB con VS Code

## IDE VS Code

Explorador de archivos y carpetas

Extensiones:
Github copilot (agente de código - IA)
Python 
Pylance
Python Debugger
Python Environments
Rainbow CSV
vscode-pdf
Markdown Preview Mermaid Support
JavaScript (ES6) code snippets (aun no instalado)

git


## Git y Github

Proyecto = carpeta = repositorio 

Git:
Sistema de control de versiones
seguimiento - versionado - rastreado

Instalacion: 
https://git-scm.com/
https://chatgpt.com/share/6ac6ffef-bf54-83e9-989f-1e6ef9fbf22c


Github:
Cuenta para trabajar en remoto
Tener un proyecto en la nube

https://github.com/
username
email
password

### guía rapida con git

https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Configurando-Git-por-primera-vez 

Como usuario

En Power Shell (terminal de Windows):

`
git --version
`
Les debe salir algo asi:

`
git version 2.53.0.windows.1
` 

Inicio de sesion

`
git config --global user.name "DanielCamarena"
git config --global user.email vcamarenap@uni.pe
`

Listar configuracion

`
git config --list
git config user.name
`

Con botones de VS Code:

- Inicializar un repositorio
- Hacer un commit: nodo
- Recomendación: activar el "auto save" en la pestaña file


Con ayuda de Github Copilot tenemos los comandos para ejecutar en terminal:

git init

git add .

git commit -m "Inicio del tiempo"

[main (root-commit) caa1f80] Inicio del tiempo
 2 files changed, 131 insertions(+)
 create mode 100644 bitacora1.txt
 create mode 100644 bitacora2.md
PS C:\Users\quant\Documents\WEB>

Para seleccionar la rama:

git branch -M main

Luego de crear en github el repositorio WEB vacío y en público obtenemos
https://github.com/DanielCamarena/WEB.git

Fijar el remoto:

git remote add origin https://github.com/DanielCamarena/WEB.git

Llevar al remoto:

git push -u origin main

Te puede pedir iniciar sesión en github

Luego de iniciar sesión sale: 

PS C:\Users\quant\Documents\WEB> git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.55 KiB | 1.55 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/DanielCamarena/WEB.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\quant\Documents\WEB>

Verificar en la web


