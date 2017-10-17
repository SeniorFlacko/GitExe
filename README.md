# GitExe
Making excercises of Git 


We learn all this commands 

git init
git add archibo_url.extension
git status
git add .
git commit -m "Primer commit 
git checkout -- .
git log
git add *.png
git add -A
git reset archibo_url.extension
git reset *.xml

git log --oneline
git log --oneline --decorate --all --graph

git status -s ( silent )
git status -s -b ( silent and brach )

* Dos guiones: Una palabra *
* Un guion: Comandos independientes pot letra *


git config --global alias.lg "log --oneline --decorate --all --graph" ( Hacer un shorcut para el log )
git config --global alias.s "status -s -b" ( Hacer alias para status )

* Toda la infotmacion grabada en el global esta  en: *

git config --global -e ( Parametros de configuracion global )

* Para salir :quit *

git config --global -l


* Diferencia entre COMMIT vs ACTUALIDAD con git diff *

* Regresion de un archivo al estado del ultimo commit con git checkout *

* Pasos ocasionales para revertir cambios añadidos al stage al ultimo commit *

git diff ( Diferencia entre el ultimo commit y como esta actualmente )

git diff --staged ( Diferencia entre el ultimo commit y como esta en el stage )

git reset HEAD README.md ( Lo quita del stage )

git checkout -- README.md ( Lo reestablece a la ultima version donde se le dio commit )


git commit -am "Mensaje de commit" ( Abreviacion para añadir al stage y ademas hacer commit )


* Para deshacer mensajes de los commits *

git commit --amend -m "Mensaje correcto para el commit"

* Para revertir el commit *

git reset --soft HEAD^

git commit --amend ( Editar: Tap a , Salir de edicion: Esc , Escribir y Salir: :wq )
<br>
git reset --soft 50cf7bc
<br>
git reset --mixed 209465c
<br>
git reset --hard 209465c
<br>
git reflog ( Ver el historial de cualquier cambio sin importar los commits )
