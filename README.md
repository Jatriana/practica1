- ¿Qué comando utilizaste en el paso 11? use el comando git resetnang--hard HEAD~1  ¿Por qué? para deshacer el ultimo commit y perder los cambios que habia hecho en el working copy (fichero  git-nuestro.md)


- ¿Qué comando o comandos utilizaste en el paso 12? use los comandos  git reflog , git reset, git restore ¿Por qué? el  git reflog para saber a que commit tenia que apuntar  1f80257 donde habia hecho la modificacion, luego el git reset 1f80257  para moverme al commit y luego git status para ver que habia una modificacion y posteriormente a un git restore para revertir los cambios.

- El merge del paso 13, ¿Causó algún conflicto? no hay conficto ¿Por qué?  el fichero git-nuesto en la rama styled solo ha sido modificado en sus lineas, mientras la rama master el git-nuestro no ha sido mofificado, por eso no genera conflicto.

- El merge del paso 19, ¿Causó algún conflicto? si causo conflicto ¿Por qué? el fichero git-nuestro en las dos ramas(styled y htmlif han sido modificdos en sus mismas lineas)

- El merge del paso 21, ¿Causó algún conflicto? No ¿Por qué? el fichero git-nuestro no ha tenido cambio en ninguna de sus lineas en las dos ramas
- ¿Qué comando o comandos utilizaste en el paso 25?git log --graph --pretty0oneline
- El merge del paso 26, ¿Podría ser fast forward? No¿Por qué? no se veria la rama title para eso se vean todos los commit es necesario que se cree un nuevo commit
- ¿Qué comando o comandos utilizaste en el paso 27?git reset -hard HEAD~1 , git add , git commit
- ¿Qué comando o comandos utilizaste en el paso 28?git checkout, git branch , git checkout rama
- ¿Qué comando o comandos utilizaste en el paso 29?git branch -D
- ¿Qué comando o comandos utilizaste en el paso 30?git checkout, git branch , git checkout rama
- ¿Qué comando o comandos usaste en el paso 32?
- ¿Qué comando o comandos usaste en el punto 33 df0909a