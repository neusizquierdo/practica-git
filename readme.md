- # ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1, es el comando que permite deshacer el último commit, y, a diferencia de "git reset HEAD ~1, también quita aquello que hay en el working copy, volviendo a estar todo tal cual estaba anteriormente.
- # ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reset 77b2e6, después de averiguar con el git reflog el número identificador del anterior commit al que queríamos volver, es decir, 77b2e6. Lo he hecho porque es una forma de volver directamente al commit que nos interesa.
- # El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?
No, styled absorbió a master sin conflicto, uniéndose en una única rama.
- # El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?
No, styled absorbió a htmlify. Para hacerlo, tuve que pasar a la rama styled con git checkout y posteriormente usando el git merche para unirlos. En cambio, tuve que volver atrás algunos pasos para recuperar este readme, que añadí desde el principio y que había sufrido cambios que no se habían guardado en otras versiones de la carpeta.
- # El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?
No, no hubo ningún conflicto, ambas ramas se pudieron unir sin problemas.
- # ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --decorate --pretty=oneline
- # El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Sí, pero se guardaría en el archivo ya existente en lugar de crear uno nuevo al final de la lista
- # ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1
- # ¿Qué comando o comandos utilizaste en el paso 28?
git merge --abort
- # ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title
- # ¿Qué comando o comandos utilizaste en el paso 30?
git checkout d79ac16 (número del paso en el que aún no habíamos deshecho el merge)
- # ¿Qué comando o comandos usaste en el paso 32?
git checkout d637158f0ea56c86f3525caec26ba2090351ebbd (número identificador del primer paso, sacado después de comprobar con git log --graph que se habían eliminado todas las ramas excepto master)
- # ¿Qué comando o comandos usaste en el punto 33?
git checkout 99f2c1e (número que identifica el commit en el que puse el título inventado al texto)