# comandos utiles de git
1.- git init -> iniciar el proyecto en un repositorio (lo primero que uno debe hacer)
2.- git add -> tomar todos los archivos que tengan desde el ultimo commit o del git init y prepararlos para una fotografia o commit para ser mas tecnicos (se puede utilizar git add . para agregar todos los archivos o simplemente git add "nombre" para tomar solo un archivo)
3.- git reset -> revierte todo lo que hace el git add (controlado tambien por un . o el nombre del archivo)
4.- git commit -> toma una fotografia del archivo el cual se guardara en la nube, tendra un id identificador que se podra ver cada commit que se realize.
5.- git checkout --. ->en caso se haya eliminado o borrado los archivos, el comando hace que todos los archivos que se encuentren en el repositorio van a ser restaurados a como se encontraban en el ultimo commit.
6.- git log -> sirve para ver todo el listado los commits en el cual se podra ver:el autor, la fecha y el codigo id que identifica al commit.
    tambien hay variciones como git log --oneline  que solo muestra un listado resumido con lo mas importante.
7.- git commit --amend -> permite arreglar el ultimo commit
8.- git branch-> para ver cuantas ramas de versiones hay en el repositorio, si agregas un nombre, creas una rama nueva
9.- git checkout -> sirve para trasladarse entre ramas
10.- git checkout -b "nombre" -> la combinacion de branch y checkout en un solo codigo.
11.- git checkout master -> permite volver a la rama master
12.- git merge "nombre de la rama (NO ESCRIBIR LA RAMA MASTER)" -> permite fusionar la rama alternativa con la rama master.
