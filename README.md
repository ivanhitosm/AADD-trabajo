## Trabajo de AADD
### Por: ivan hitos Marquez
*comandos importantes que recordar*

-CONFIGURAR GIT:
~~~
git config --global user.email correoelectronico
~~~
-CREAR NUEVO REPOSITORIO:
~~~
git init
~~~
-CREAR COPIA LOCAL:
~~~
git clone url del git
~~~
-AGREGAR ARCHIVOS A STAGING AREA:
~~~
git add -A nombre_de_archivo
~~~
-AGREGAR A LOCAL REPOSITORY:
~~~
git commit –m “mensaje”
~~~
-VER LISTA DE ARCHIVOS CAMBIADOS Y AÑADIDOS:
~~~
git status
~~~
-ENVIAR CAMBIOS DE RAMA PRINCIPAL DE LOS REPERTORIOS REMOTOS:
~~~
git push origin nombrerama
~~~
-CAMBIAR ENTRE RAMAS O CREARLAS:
~~~
git checkout nombrerama
~~~
-CONECTARSE A REPOSITORIO REMOTO:
~~~
git remote add origin <dirección>
~~~
-LISTAR, CREAR O BORRAR RAMAS:
~~~
git branch
git Branch -d nombrerama
~~~
-FUSIONAR CAMBIOS REALIZADOS EN EL REPOSITORIO LOCAL:
~~~
git pull
~~~
-FUSIONAR RAMA CON OTRA RAMA ACTIVA:
~~~
git merge <nombrerama>
~~~
-VER CONFLICTOS EN RAMAS:
~~~
git diff
~~~
-RESETEAR INDEX Y EL DIRECTORIO AL ULTIMO ESTADO
~~~
Git reset - -hard HEAD
~~~
git checkout -b nombre_del_branch origin/nombre_del_branch
git pull origin nombre_del_branch
~~~
-PARA REVERTIR
~~~
git revert origin nombrerama
git revert HEAD lo hace para revertir el commit
~~~
-PARA ELIMINAR UN ARCHIVO QUE NO QUIERO SUBIR
~~~
git reset HEAD nombre.extensiongit
