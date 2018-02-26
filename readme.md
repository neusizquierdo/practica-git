- # ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1, es el comando que permite deshacer el último commit, y, a diferencia de "git reset HEAD ~1, también quita aquello que hay en el working copy, volviendo a estar todo tal cual estaba anteriormente.
- # ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reset 77b2e6, después de averiguar con el git reflog el número identificador del anterior commit al que queríamos volver, es decir, 77b2e6. Lo he hecho porque es una forma de volver directamente al commit que nos interesa.
- # El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?
No, styled absorbió a master sin conflicto, uniéndose en una única rama.
- # El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?
No, styled absorbió a htmlify. Para hacerlo, tuve que pasar a la rama styled con git checkout y posteriormente usando el git merche para unirlos. En cambio, tuve que volver atrás algunos pasos para recuperar este readme, que añadí desde el principio y que había sufrido cambios que no se habían guardado en otras versiones de la carpeta.
- # El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué? 
- # ¿Qué comando o comandos utilizaste en el paso 25?
- # El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
- # ¿Qué comando o comandos utilizaste en el paso 27?
- # ¿Qué comando o comandos utilizaste en el paso 28?
- # ¿Qué comando o comandos utilizaste en el paso 29?
- # ¿Qué comando o comandos utilizaste en el paso 30?
- # ¿Qué comando o comandos usaste en el paso 32?
- # ¿Qué comando o comandos usaste en el punto 33?- - 