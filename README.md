# Repositorio campusciff
## Ejercicio básico
**2.1. Creo el repositorio campusciff a través de la página de GitHub.**

<img src="https://github.com/aguerra952/campusciff/blob/master/screenshots/creo-repositorio.png"/>

**2.2. Clono el repositorio creado en mi disco local con el comando:**

`git clone https://github.com/aguerra952/campusciff.git`

**2.3. Creo el archivo README.md en el repositorio local y lo modifico. Ahora añado el archivo para hacer commit con el siguiente comando:**

`git status
git add . --a`

**2.4. Una vez añadido el archivo README hago un commit:**

`git commit -m "Commit inicial"`

**2.5. Subo los cambios realizados a GitHub con el comando:**

`git push`

**2.6. Creo en mi repositorio local una carpeta llamada 'privada' y un archivo llamado 'privado.txt'.**

**2.7. Luego creo un archivo .gitignore y dentro de este escribo el nombre de los archivos que quiero ignorar en GitHub. Ahora subo los cambios a la nube:***
~~~
git status
git add . --a
git commit -m "Añado el archivo .gitignore"
git push
~~~~
**2.8. Creo un fichero llamado '1.txt' en mi repositorio local.**

**2.9. Creo un tag llamado 'v0.1' en mi repositorio y confirmo si se ha creado con el siguiente comando:**
~~~
git tag -a v0.1 -m "Version 0.1 - campusciff"
git tag -n
~~~
**2.10. Subo el tag que he creado más el archivo:**
~~~
git status
git add . --a
git status
git commit -m “Añadido el fichero '1.txt' y creado el tag 'v0.1'”
git push
git push --tags
~~~
**2.11. Edito cambio mi foto de perfil, hago mi email público y activo la doble verficación:**

<img src="https://github.com/aguerra952/campusciff/blob/master/screenshots/foto-perfil.png"/>

<img src="https://github.com/aguerra952/campusciff/blob/master/screenshots/email-publico.png"/>

<img src="https://github.com/aguerra952/campusciff/blob/master/screenshots/doble-verificacion.png"/>

**2.12. Sigo a mis compañeros, sus repositorios y pongo estrellas a los repositorios que me interesen:**

<img src="https://github.com/aguerra952/campusciff/blob/master/screenshots/compa%C3%B1eros.png"/>

<img src="https://github.com/aguerra952/campusciff/blob/master/screenshots/sigo-repositorios.png"/>

**2.13. Creo una tabla utilizando sintaxis markdown y dentro escribo los enlaces de GitHub de mis compañeros:**

|NOMBRE|GITHUB|
|---|---|
| Sebastián Berdonces | https://github.com/sberdonces1996 |
| Juan Manuel Casado | https://github.com/JuanManuelCasado |
| Rafa Domínguez | https://github.com/rafadominguez71 |
| David Bueno | https://github.com/dvidgb |
| Rafael Palomino | https://github.com/solkido |
| Luis Manuel | https://github.com/luismamm |

Ahora guardo los cambios:

~~~
git status
git add . --a
git commit -m "GitHub de compañeros añadido en el archivo README.md"
git push
~~~

**2.14. Hago colaborabor a asanzdiego:**

<img src="https://github.com/aguerra952/campusciff/blob/master/screenshots/hago-colaborador.png"/>

## Ejercicio avanzado
**2.2. Creo una rama llamada 'v0.2' y me posiciono en ella.**

`git checkout -b v0.2`

También se podría hacer de la siguiente manera:
~~~
git branch v0.2
git checkout v0.2
~~~
**2.3. Creo un fichero llamado '2.txt' y lo añado a la rama v0.2**
~~~
git add . --a
git commit -m "Añadido fichero '2.txt' a la rama v0.2"
~~~~
**2.4. Subo la rama a la nube.**

`git push origin v0.2`
