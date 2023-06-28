# practica1git
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
 porque con reset nos movemos a HEAD y la rama actual a un commit anterior, por este caso HEAD~1 hace referencia al commit padre mas reciente

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog para poder listar los commit y sacar el ID, y luego 
git reset --hard con el id del commit 
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
aunque se toco el mismo archivo no me genero conflico, si 
existe un conflicto seria por hacer cambios en las mismas lineas
del archivo lo cual se deberia de resolver seegun las neecesidades
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
tampoco me dio conflicto, solo cambio el archivo segun tenia 
htmlify ya que styled la absorbio.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
no, me cambie a la rama main luego hice merge con styled, 
quizas no me ha dado conflicto anteriormente porque los cambios 
los hice al archivo entero y no linea por linea,
- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph
sale como una linea de tiempo para ver nuestros commit
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
si, porque no eistieotn conflictos entre ramas, git simplemente 
se mmueve a main
- ¿Qué comando o comandos utilizaste en el paso 27?
git reset --hard HEAD^
- ¿Qué comando o comandos utilizaste en el paso 28?
git checkout .
- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog
git reset --hard ID
git merge --no-ff title
- ¿Qué comando o comandos usaste en el paso 32?
git reflog
git checkout ID
- ¿Qué comando o comandos usaste en el punto 33?
git reflog
git checkout ID
