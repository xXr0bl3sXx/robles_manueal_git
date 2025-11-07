## Crea una carpeta .git y empieza a rastrear cambios.
mkdir mi-proyecto
cd mi-proyecto
git init
## Descarga una copia completa del repositorio
git clone https://github.com/usuario/proyecto.git
cd proyecto
## Marca qué cambios van a incluirse en el próximo commit.
git add README.md
git add .
## Crea un punto de guardado con mensaje.
git commit -m "Añadir manual básico de comandos Git"
## Lista commits con autor, fecha, mensaje y hash.
git log
git log --oneline
## Mueve tu directorio de trabajo a otra rama o commit.
git checkout nombre-rama
git checkout -b nueva-rama
## Gestiona las ramas (líneas de trabajo paralelas).
git branch
git branch nueva-rama
git branch -d vieja-rama
## Sube tus commits a GitHub.
git push origin main
## Trae cambios del remoto y los fusiona en tu rama actual.
git checkout main
git merge nombre-rama
## Integra cambios de una rama en otra.
git checkout main
git merge nombre-rama
