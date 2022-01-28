# GIT
## PASOS PARA HACER COMMIT:
```
git init
git branch -M main
git add .
git commit -m "first commit"
git remote add origin https://github.com/JEduardoCC/Guia-Git.git
git push -u origin main
```
## COMANDO DE GIT:

```
git init
```
- 
```
git status
```
- Poder listar y ver si los archivos estan listos para subir

- :eyes: en caso los archivos no esten listos se veran de color rojo y cuando lo esten seran de color verde
```
git add .
git add "nombre_de_archivo"
```
-Se encarga de agregar los archivos a la memoria de GIT, es decir los guarda en un stash
```
git commit -m "comentario"
```
-Crear un punto en la linea de tiempo :time: de nuestros cambios y a estos se le es posible adjuntar un comentario
- :eye: Los comentarios deben estar relacionados a los cambios que se realizo, esto es una recomendacion.
```
git push origin main
```
-Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso GIT HUB.
```
git pull origin main
```
- Sirve para poder descargar los camibos de nuestro repositorio en la nube, en este caso GIT HUB.
```
git branch
```
- Sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro actualmente.
```
git checkout -b nombre_de_branch
```
- Sirve para crear un branch nuevo y poder trabajar en el
```
git checkout nombre-de-branch
```
- Sirve para poder moverme entre ramas
- :eye: Si el checkout no tiene el -b, solo es para moverse entre ramas.