# Clase 05 - Git

## Para crear un repositorio de GIT

```sh
git init
```
## ver en qué estado estan los archivos y en que area
```sh
git status
```


## Areas del Repositorio de GIT

3 areas

* Working directory (WD): Directorio de trabajo donde se van agregando o quitando los archivos durante el desarrollo
* Staging Area(SA): Area de control de cambios. Area temporal o intermedia
* Local Repo(LR): una caja donde voy a ir teniendo todas las fotos del desarrollo que voy sacando

## Estados de los archivos

* Untracked: archivos que estan en el wd pero GIT no les esta dando seguimiento
* Unmodified: archivos que GIT ya esta siguiendo y con respecto al WD no fueron modificados
* Modified: archivos que se encuentran en el respositorio(estan siendo seguidos por GIT) pero difieren con lo que se encuentra actualmente en el WD
* Staged: Archivos que se encuentran en el area temporal/intermedia    

# Agrego al area de confirmacion el archivo o archivos

```sh
git add <nombre-archivo>
git add <nombre-archivo>
git add . # agrega todos los archivos
```

