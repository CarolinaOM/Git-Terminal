# Aqui veremos los comandos mas utilizados en git

![Banner de linux](./assets/git.png)

- git add

Añade cambios de archivos en el directorio

```bash
git add
ejemplo: git add archivo.txt
```
-git commit

Toma cualquier cambio escrito en el índice y crea un nuevo objeto de confirmación que apunta a él y establece la rama para que apunte a esa nueva confirmación.

```bash
git commit
git commit -m ‘committing added changes’
```


-  git config

Define los valores de la configuracion git

```bash
git config --global user.name "camputer"
git config --global user.email "your_email@example.com"
```

- git init

Se emplea para crear un nuevo repositorio 

```bash
git init
```

- git log

Muestra una lista de configuraciones en una rama

```bash
git log
```

- git pull

Obtiene los archivos del repositorio remoto y los combina con el local.

```bash
git pull origin
```

- git push

Envía todos los objetos modificados localmente al repositorio remoto.

```bash
git push origin master
```

- git remote

Muestra todas las versiones remotas de tu repositorio. 

```bash
git remote origin
```


- git status

Muestra el estado de los archivos 

```bash
git status
```
