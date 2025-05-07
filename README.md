el principio d mi project xd
# curso git/github scesi 1-2025

# cursopython with Vetdy03
echo "# cursoGit1-2025" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/vetdy03/cursoGit1-2025.git
git push -u origin main
# Comandos basicos del git
- Agregar al git todo muchas veces se debe ubicar en el directotio principal
```makdown
git add .
```
- Hacer commit 
```makdown
git commit -m "comentario que quieres ref."
```
- hacer un push al repositorio remoto osea enviarlo `ya sea main o dev`
```makdown
git push -u origin main
```
- Traer todos los cambios del remoto al local
```makdown
git pull -u origin main
```
- Guardar tus cambios actuales (por si acaso) en local
```makdown
git stash
```
- Aplicar los cambios guardados en local al local
```makdown
git stash pop
```
- Restaurar un commit en git
```makdown
git restore --staged Nombre.extension
```
# comandos para mergear desde consola
Paso 1 Clone el repositorio o actualice su repositorio local con los `últimos cambios.`

```makdown
git pull origen main
```
Paso 2 `Cambie a la rama base` de la solicitud de extracción.
```makdown
git checkout main
```
Paso 3 Fusiona la rama de la cabeza con la rama base.
```makdown
git merge dev
```
Paso 4 Empuje los cambios.
```makdown
- git push -u origin main
```
# como restaurar un git add
```makdown
git restore
```
# rama local main está desactualizada respecto a la rama remota main
- Actualizar la rama local antes de hacer push Esto traerá los cambios remotos y aplicará tus cambios encima
```makdown
git pull origin main --rebase
```
-  Forzar el push Sobrescribirá el remoto, si estas seguro
```makdown
git push -f origin main
```
- 
- 
```makdown

```
- 
