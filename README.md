# Repositorio campusciff
## Ejercicio básico
2.1. Creo el repositorio campusciff a través de la página de GitHub.

2.2. Clono el repositorio creado en mi disco local con el comando:

`git clone https://github.com/aguerra952/campusciff.git`

2.3. Creo el archivo README.md en el repositorio local y lo modifico. Ahora añado el archivo para hacer commit con el siguiente comando:

`git status
git add . --a`

2.4. Una vez añadido el archivo README hago un commit:

`git commit -m "Commit inicial"`

2.5. Subo los cambios realizados a GitHub con el comando:

`git push`

2.6. Creo en mi repositorio local una carpeta llamada 'privada' y un archivo llamado 'privado.txt'.

2.7. Luego creo un archivo .gitignore y dentro de este escribo el nombre de los archivos que quiero ignorar en GitHub. Ahora subo los cambios a la nube:
~~~
git status
git add . --a
git commit -m "Añado el archivo .gitignore"
git push
~~~~
2.8. Creo un fichero llamado '1.txt' en mi repositorio local.

2.9. Creo un tag llamado 'v0.1' en mi repositorio y confirmo si se ha creado con el siguiente comando:
~~~
git tag -a v0.1 -m "Version 0.1 - campusciff"
git tag -n
~~~
2.9. Subo el tag que he creado más el archivo:
~~~
git status
git add . --a
git commit -m “Añadido el fichero '1.txt' y creado el tag 'v0.1'”
git push
git push --tags
~~~