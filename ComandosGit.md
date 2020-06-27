# Comandos Git

## Inicializar proyecto Git

Inicializa un repositorio Git, con este comando se crea la carpeta .git, si cometes el error de hacer un "git init" en el disco "c:" no te preocupes, solo debes eliminar la carpeta .git que creaste 

```groovy
git init
```

## Cambios en tu Computadora (Local)

Es importante entender que git trabaja en tu computadora local, esto te permite poder guardar los distintos cambios de tu código.

```groovy
//Obtiene un listado de todos los archivos modificados
git status

//Agrega todos los archivos al commit
git add .

//Guarda todos los archivos modificados en tu computadora
git commit -m "Mensaje del commit"

//Muestra todos los commit realizados en el proyecto
git log

//Volver tus cambios al ultimo commit (En caso de problemas)
git checkout -f
```

## Trabajo con Ramas

Es importante entender que Git permite manejar las versiones de código, por lo tanto es muy importante trabajar con ramas a la hora de desarrollar proyecto entre muchos desarrolladores.

```groovy
//Lista todas las ramas de tu computadora
git branch

//Lista todas las ramas, las de tu computadora y las que son remotas
git branch -va

//Crear una rama
git branch <nombre-rama>

//Crear una rama y cambiarte a esa rama creada
git checkout -b <nombre-rama>

//Eliminar una rama
git branch -d <nombre-rama>

```