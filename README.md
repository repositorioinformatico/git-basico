# git-basico
mkdir cursogit
cd cursogit
mkdir 01
cd 01
git init
touch f1.txt
nano 20221007.txt
(Escribimos dentro contenido)
git status (y confirmamos en qué estado están ficheros)
git rm --cached <file> (quitar ficheros del staged)
git add <file> (para añadir fichero al staged)
git add . (alias de añadir todo)
git commit -m "Mensaje descriptivo Corto" (commiteamos)
git commit (abrirá el editor por defecto de tu terminal)
git diff
