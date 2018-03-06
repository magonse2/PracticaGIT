¿Qué comando utilizaste en el paso 11?
$ git reset -- hard HEAD~1
Porque permite borrar el último commit realizado y sus cambios.

¿Qué comando o comandos utilizaste en el paso 12?
Utilizé git reflog para obtener el código del commit y poder mencionarlo mas tarde en git reset --hard 421893c y de esta manera poder revivir el commit borrado.

El merge del paso 13 ¿Causó algún conflicto? 
Si, aparecia un mensaje que decia Already Up To Date, porque eso significa que la rama master ya es el padre de la rama styled y por lo tanto no se puede realizar.

El merge del paso 21 ¿Causó algún conflicto?
No me causó ningún conflicto porqué la rama parent si que es capaz de absorbir al son que seria la rama styled.

¿Qué comando o comandos utilizaste en el paso 25? 
git graph

El merge del paso 26, ¿Podría ser fast forward? 
Si, puede utilizarse un merge sin el elemento --no-ff y de esta manera no seria fastforward

¿Qué comando o comandos utilizaste en el paso 27?
git reset --hard y el numero del commit del merge

¿Qué comando o comandos utilizaste en el paso 28?
git checkout --Don-Quijote.md

¿Qué comando o comandos utilizaste en el paso 29?
git branch title -d

¿Qué comando o comandos utilizaste en el paso 30?
git merge --no-ff title, pero no se puede rehacer ese merge porque se acaba de borrar la rama title jajajaj

¿Qué comando o comandos utilizaste en el paso 32?
git checkout y el numero del primer commit

¿Qué comando o comandos utilizaste en el paso 33?
git checkout y el numero del commit donde se encuentra el titulo que añadí





