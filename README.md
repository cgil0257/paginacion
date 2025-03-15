# Prática de paginación PHP
## Iniciar
git init     comando inicial
git add .    agregar espacio y luego el punto
git remote add origin https://github.com/cg      ppara ir al repositorio remoto
git commit -m "first commit"    para inicializar el commit
git add README.md          para establecer la descripción general del archivo (commit)
git status -s             para conocer el material en README
?? README.md            implica que README  está vacío
M README.md             significa que README ya tiene información
                        en este caso ya no se utiliza git add
git commit -am "edit readme"       inicializar en main o master branch
git branch test         crear branch llamada test. No es conveniente trabajar en Main branch
git checkout test       cambiar de main branch a test branch
git remote -v         ir a repositorio remoto
origin (https://...repositorio remoto)(fetch)
origin (https://...repositorio remoto)(push)
git push origin test 
git config --global --list    el dominio pertenece a x usuario
git config --global --unset user.email usuario x   borrar al usuario x
git config --global user.name cgil0257     nuevo usuario
git config --globsl user.email souve...    nuevo correo del usuario
git branch master        se crea rama master
git checkout master      se cambia a rama master
git merge test          se fusiona test con master
git branch -d test      se elimina branch test
git branch prueba              nueva rama
git commit -am "se edito archivo"        se inicia nuevo commit
git checkout master        cambiar de subrama prueba a rama master
git committ -am "se edito archivo master" 
git branch -d prueba        se elimina branch prueba
git log --oneline           indica las ediciones elaboradas
git tag -a versio´n1.0 -m "primera etiqueta"
git tag -a 'version1.0 -m 'primera etiqueta