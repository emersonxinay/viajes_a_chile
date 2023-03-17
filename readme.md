# viajes a chile
Link de pagina desarrollada
https://emersonxinay.github.io/viajes_a_chile/

# Recordando git y github
## comandos mas usados de git 

para iniciar en git 
```bash
git init
```
para agregar todos los cambios
```bash
git add --all 
```
o 
```bash
git add .
```
para regresar a estado normal del ultimo commit pero con respecto a archivos modificados 
```bash
git reset --hard
```

para crear nuestra version usamos el commit 
```bash
git commit -m "titulo del commit"
```
commit solo para archivos que existen y modificaste
```bash
git commit -am "titulo del commit"
```

para reconstruir todo los archivos y modificaciones sobre el último commit.
```bash
git checkout -- .
```
para verificar cuantos commit tengo 
```bash
git log
```
para cambiar el nombre del último commit ( considerar: presionar la letra "w" seguido de la letra "a" y luego editar. Para guardar presionar "esc" luego " :wq! ") 
```bash
git commit --amend
```

para crear una rama 
```bash
git branch nombre_rama
```
para ubicarnos hacia una rama especifica 

```bash
git checkout nombre_rama
```

para crear y dirigente rapidamente a una nueva rama 
```bash
git checkout -b nueva_rama 
```
para ver todo el listado de ramas
```bash
git branch
```
para eliminar una rama especifica
```bash
git branch -d rama_a_eliminar
```
# github
para crear el repositorio remoto de github (recomendación, copiar todo el link cuando creamos nuevo repositorio desde github)

```bash
git remote ruta_del_github
```

para subir a github 
```bash
git push -u origin rama_a_subir 
```

para saber si hay actualizaciones en el repositorio de github

```bash
git fetch
```

para descargar todas las actualizaciones pero especificamente de una rama que deseas. (recomendación, ubicarse en la rama que deseas descargar los cambios)

```bash
git pull
```

# configuración de git
para ver la version de git 

```bash
git --version
```
para configurar nombre 
```bash
git config --global user.name "emerson espinoza"
```
para configurar correo ( recomendación, usar la misma cuenta de github)
```bash
git config --global user.email "correo@gmail.com"
```





















