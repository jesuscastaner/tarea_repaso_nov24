# tarea_repaso_nov24
Tarea de repaso de EEDD - 24/11/2024

## primer commit
* Creo la estructura de directorios utilizando `mkdir`.
* Creo los archivos con `touch`.
* Abro el archivo ".gitignore" en Visual Studio Code con `code .` (esto me abre todo el repo).
* Incluyo dentro los elementos a ignorar por git:
    * .DS_Store (son unos archivos que crea automáticamente Finder en Mac)
    * local_config/
    * *.tmp
    * *.env
    * el propio ".gitignore".

* Compruebo que git detecta los cambios con `git status`.
* Añado los archivos al stage con `git add .`.
* Compruebo que están correctamente preparados nuevamente con `git status`.
* Hago commit con `git commit`, añadiendo una descripción con `-m "..."`.

## segundo commit
* Creo la rama "rama_nueva" con `git branch nueva_rama`.
* Compruebo que se ha creado correctamente con `git branch` y después me traslado a ella con `git switch nueva_rama`.
* Regreso a Visual Studio Code y edito este archivo "README.md".
* Compruebo que git detecta los cambios con `git status`.
* Añado todo al stage con `git add .`.
* Hago commit con `git commit -m "..."`.
* Cambio a la rama main con `git switch main`.
* Hago merge desde nueva_rama a main con `git merge origin nueva_rama`.