
# Comando para listar las ramas de mi repositorio 
- gti branch
- git branch -v  (este da mas informacion)

# Comando para crear una rama
- git branch nombre_rama

# Comando para cambiar de ramas 
- git checkout nombre_rama
- git switch nombre_rama (hace lo mismo que la anterior)
- git checkout -b nombre_rama (Crea la rama y hace el cambio)

# Comando para eliminar una rama 
- git branch -D nombre_rama

# comando para cambiar el nombre de una rama 
- git branch -M nuevo_nombre   (Se le cambia el nombre a la rama done este parado).

# Para ignorar una archivo 
- Si el archivo no esta en git simplemente en la carpeta .gitignore se guarda la ruta- 
- Si el archivo ya esta en git la ruta es la siguiente. 
  1. Accedemos a la carpeta dodne esta el archivo= 
    cd nombre_carpeta
  2. listamos lo que esta en la carpeta = 
    ls
  3. se elimina del git y se saca de la cached  = git rm --cached nombre_archivo
  4. volviendo a la carpeta principal, ay que volver a hacer un add commit pata que todo quede guardado. 

  # Crar un comando  personalizado 
  - git config --global alias.lg log oneline 
    (lg es el nombre del alias log.online es lo que quiero que haga ese alias)

