# Comando para conectar el git local con el git en la nube
- git remote add nombre_conexion url_conexion

# Comando para clonar o traer un repositorio de git remoto a git local.
- git clone url_conexion

# Comando para listar las conexiones remotas
- git remote -v

# Comando para eliminar una conexion remota 
- git remote nomove nombre_conexion

# Comando para enviar informacion a la nube
- git push 
- git push nombre_Conexion nombre_Rama 
- git push -u nombre_Conexion nombre_Rama  (al poner el -u, si la conexion no existe la crea).
- git push --all

# comandos para obtener cambios o la informacion que hay en el git remoto
- git pull 
- git pull nombre_conexion nombre_rama

