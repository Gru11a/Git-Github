

# 📋Nota:
	
	El propósito es investigar mas de esta herramienta es aprender y utilizar en mis proyectos personales y profesionales. Las notas que realice son apuntes que considero importantes y que me pueden ayudar en futuras referencias.

# 🔗Referencias:

	He tomado de referencia el canal de MoureDev, por que explica claro y tiene gran experiencia en el campo de desarrollo, pueden seguirlo si gustan:
	https://youtu.be/3GymExBkKjE?si=DMHTAkJNLqJ44Ued
	

# 👉Comentarios Personales:

	https://github.com/Gru11a/git-github/blob/main/GIT-GitHUB/git-github.png

## What is GIT - GITHUB


### GIT

	- Control de versiones
	- Código abierto 
	- Distribuido

### GITHUB

	- Plataforma de alogamiento de codigo

## Resources:

	https://git-scm.com/
	https://git-scm.com/book/en/v2
	https://github.com/
	https://training.github.com/downloads/github-git-cheat-sheet/
	https://docs.github.com/en

## Context:	

	https://es.wikipedia.org/wiki/Git
	
## Instalation of git hub

	https://git-scm.com/downloads


# Let's go

## Version

	git --version

## Help

	git -h

## Comands 

	ls
		listado de todos los directorios
	
	cd
		para moverse a otra carpeta
	
	cd ..
		para retroceder de ubicacion
	
	pwd
		para ver donde me encuentro
	
	mkdir "nombre"
		crea una carpeta
	
	code.
		para abrir el visual studio code

## Configuracion de GIT

	asociado a alguien
		nombre de usuario y email
		
	git config --global user.name "nombre"
	git config --global user.mail "grulla@mail.com"

## GIT INIT
	
	touch prog.py
	git init
		para que en la carpeta que se indique inicie a funcionar git

	Http://ohmyz.sh
		para personalizar la terminal

## Ramas en GIT

	git branch -m main
		para cambiar el nombre de la rama principal

## Git ADD y COMMIT

	git status
		para ver el estado del proyecto
		
	git add hellogit.py
		para agragar el archivo para se treceable por git
		
	git commit -m "Commit sobre..."
		para ingresar un comentacio de una vez
		
## GIT LOG y STATUS

	git log
		para ve si se ha creado la imagen y observar la trasabilidad

## GIT CHECKOUT Y RESET

	git checkout hellogit2.py
		para ubicarnos a un momento exacto
	
	git reset
		para volver el estado de la ultima fotografia
	
	git log --graph
		para verlo como rama
	
	git log --graph --pretty=oneline 
		para ver el movimiento en una linea
	
	git log -- grapgh --decorate --all --oneline
		para ver mas claro el moviento o actualizacion.

## GIT ALIAS

	git config --global alias.tree "log -- grapgh --decorate --all --oneline"
		git tree

## GITGNORE

	touch .gitignore
		para crear una carpera para incluir carpetas que no debe tomar en cuenta para el proyecto.
	En el archivo creado "gitignore" ingresamos los nombre de archivos a ignorar
		
		**/.nombre
			con los asteriscos le indicamos donde sea

## GIT DIFF

	git diff
		para ver lo que ha cambiado

## Checkout

	Para desplazarse por los diferentes estados

	git checkout "hash"
		para ubicarse en se estado con el hash
	git checkout "PROYECTO.PY"	
		
	git checkout HEAD
		para indiar que estado se desea trabajar

## GIT RESET HARD Y REFLOG

	git reset --hard
		descartar cambios, pero con hard es mas 
	git reflog
		historial completo de interacciones

## GIT TAG

	Para etiquetar referencias importantes
	
	git tag project_1
		como colocar un nombre a ese punto
		
	git add .
		agrega todo lo pendiente
	
	git tag
		para ver listado de tags
	
	git checkout tags/nombredeltag
		para moverse con tags
	
	git checkout main

## GIT Branch y Switch

	git branch nombre
		para crear una rama

	git switch nombre
		para moverse a la rama que se desea trabajar

## Git Merge

	Para combinar los cambios
	git merge main
		combinar los datos a nuestra rama

## Conflictos en GIT

	cuando varios equipos modifican el misco codigo 

	en el editor de codigo se observa lo que ha sido modificado y se deja lo que corresponda	

## GIT STASH

	para almacenar temporalmente, algo en que se esta trabajando
	
	git stash
		para guardarlo temporalmente
		
	git stash list
		para enlistar los stash
		
	git stash pop
		para recuperar o volver donde se guardo
		
	git stash drop
		para borrar los stash guardados	

## Reintegración en GIT

Cuando se ha terminado alguna funcionalidad en alguna rama, y se desea integras a la rama main.

1-revisar si hay conflictos y comparar ramas
	git diff rama1

2-combinar con el proyecto principal
	git merge rama1

3-verificamos el estado
	git status
	

## Eliminación de ramas

	git branch -d login
		para eliminar la rama 


## Introducción a GitHUb

## Page:

	https://github.com/


## Github primeros pasos

	[GitHub Docs](https://docs.github.com/es)

## Repositorio personal

	Creacion de cuenta y conocer la plataforma
	
## Local y remoto

	Para sincronizar nuestros proyectos con Github
	
## Autenticación SSH

	[Authentication documentation - GitHub Docs](https://docs.github.com/en/authentication)

He utilizado windows:

[Generating a new SSH key and adding it to the ssh-agent - GitHub Docs](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

```powershell
Get-Service -Name ssh-agent | Set-Service -StartupType Manual
Start-Service ssh-agent
```

## Repositorio proyecto

Se crea un nuevo repositorio

## Git Remote

	git remote add origin https://github.com/Gru11a/git-github1.git

	git push -u origin main

## Subida Proyecto

## Git Fetch y Pull

### fetch

	Solo descarga el histotial de cambios sin los cambios

### git pull 

	descargar el historial y los cambios
		

## Git Clone

	git clone git@github.com:Gru11a/git-github1.git
		para descargar el proyecto en el equipo
	
## Git Push

	para subir los commits o cambios a github

## GitHub fork

	para copiar otro proyecto en nuestro repositorio 

## Flujo Colaborativo

	Cuando trabajamos en el proyecto compiado de un fork, y luego enviar los cambio al proyecto original

	Importante para verifivar sincronicaion Sync fork

## Pull Request

	Para contribuir con el proyecto original

 1-Se preciona en contribute se envia la pull request.

2- En el proyecto original sale una solicitud de pull request, se revisa si de aceptan.

3- Luego de aceptados para mostrar los cambios se debe Merge pull request.


## Herramientas graficas

### Gitkracken
	
	para proyectos libres
	
### Sourcetree
	
	para proyectos privados

### Git-fork

	otra herramienta

## Git & GitHub Flow

Flows de trabajo

https://www.gitkraken.com/learn/git/git-flow
https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow

## Git Cherry-Pick Y Rebase

### Cherry Pick
	
	La posibilidad de ir a un commit concreto, y traerlo a la rama que deseamos

	git cherry-pick hash
	git cherry-pick --i
	git cherry-pick --continue
	git cherry-pick --abort
### Rebase

	Para traer una rama a un punto concreto y modifica el historial de los commits

	git rebase 	--i
	git rebase 	--continue
	git rebase 	--abort

## GitHub Pages & Actions

Para paginas en github
	https://pages.github.com/

Para automatizacion
	https://github.com/features/actions

		


