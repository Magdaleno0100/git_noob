# git_noob

## git

### Comandos básicos

Pasar al área de stage con : 

    git add <archivo/carpeta>

Usa 
    
    "git restore --staged <archivo>..."

para sacar del área de stage

Para ver el histórico de cambios:
    
    git log 

Para viajar entre commits:

    git checkout <identificador de commit(hash)>

Si quieres crear una nueva rama para mantener los commits que has creado,
puedes hacerlo (ahora o después) usando -c con el comando checkout. Ejemplo:

    git switch -c <nombre-de-nueva-rama>

O deshacer la operación con:

    git switch -


