## COMANDOS
`git add` 		Sirve para incluir los cambios del o de los archivos en el siguiente commit: 
	* `git add <archivo>`
	* `git add -A` para incluir todos los arvhivos.

`git commit`	Sirve para establecer un punto de controlen el proceso de desarrollo, crear una versión, al cual se puede volver despues: 
	`git commit -m "mensaje descriptivo sobre se hace en ese commit"`

`git push`		Sirve para enviar los commits al repositorio remoto: 
	`git push <nombre-remoto> <nombre-de-rama>`

`git branch`	Permite crear ramas, tiene subcomandos para enumerar y elimnar ramas, así como cambiar su nombre: 
	* `git branch --list`				Enumera todas las ramas del repositorio.
	* `git branch <nombre-de-rama>`		Crea una nueva rama con el nombre puesto.
	* `git branch -D <nombre-de-rama>`	Elimina la rama especificada.
	* `git branch -m <nombre-de-rama>`	Cambia el nombre de la rama actual a <nombre-de-rama>.
	* `git branch -a`					Enumera todas las ramas remotas.

`git checkout` 	Sirve para cambiarse de una rama a otra: 
	`git checkout <nombre-de-la-rama>`

`git log`		Sirve para explorar las revisiones anteriores de un proyecto. Proporciona varias opciones de formato para mostrar las instantáneas confirmadas.

`git status`	Sirve para obtener información sobre el estado de la rama actual.

`git init`		Inicializa un nuevo repositorio de Git.

`git config` 	Establece las opciones de configuración de inicialización de Git.
