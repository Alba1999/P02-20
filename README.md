# P02-20

##Creación de un repositorio
1. Se inicializa el repositorio en local usando el comando:
`git init` 

2. Se crea el repositorio remoto:
![Creacion Repositorio](/P2/ASSET/CreaRepoRemo.png)
Format: ![Creacion Repositorio](url)

3. Se especifica la url del repositorio remoto en local, para ello usamos el comando:
`git remote add origin https://github.com/Alba1999/P02-20.git`

4. Luego hacemos un cambio en nuestro repositorio local y confirmamos estos cambios usando la secuencia de comandos:
`git add ./*` para agregar el seguimiento de git a todos nuestros cambios
`git commit -m"[Aquí va un comentario]"` para confirmar estos cambios en nuestra version local

5. Subimos los cambios a remoto con el comando:
`git push origin master` donde el origin es nuestro repositorio remoto y master es la rama o __branch__
