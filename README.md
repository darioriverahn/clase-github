CONFIGURACION
----------------------------------------------------------------------
Una vez instalado git, debes configurar lo siguiente:

1. git config --global user.name "ddriverahn"
2. git config --global user.email "ddriverahn@ggg.com"

Generando tú public Key:
1. ssh-keygen

Leer dicha llave para copiarla en GitHub
1. cat ~/.ssh/id_rsa.pub 


COMANDOS GENERALES
----------------------------------------------------------------------
1. git status:		estado del repositorio configurado


----------------------------------------------------------------------
PROCESOS EN GITHUB
----------------------------------------------------------------------

Clonar un proyecto
1. mkdir <nombredeproyecto> (crear el directorio)
2. git init para instanciar el repositorio
3. git remote add <Url en git del proyecto>(si no presenta msg esta todo bien)
4. git pull origin master (se empieza a descargar el proyecto y listo a trabajar)

Iniciar el directorio
1. git init     Iniciar el nuevo repositorio(en el directorio que hemos creado anteriormente)

Crear un archivo
1. touch <nombrearchivo>
2. git add<nombrearchivo> o git add .
3. git commit -m <"Descripcion del cambio entre comillas">

Creacion de Rama
1. git branch <nombredelarama>

Agregar una rama a la cuenta git
1. git push origin <nombredelarama>

Moverte a una rama a otra
1. git checkout <nombredelarama>

Borrar una rama local
1. git checkout master
2. git branch -d <nombredelarama>

Borrar una rama local
1. git checkout master
2. git push origin:<nombredelarama>

Agregar una rama al archivo master o principal
1. git checkout master
2. git merge <nombredelarama>


NOTAS GENERALES
----------------------------------------------------------------------

1)Fork: Crea una nueva versión del proyecto al que quiero colaborar dentro de github
