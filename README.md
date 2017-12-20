# clase-github
Este es un tutorial de mis primeros pasos en  Git Hub 


Una vez instalado git, debes configurarlo:

git config --global user.name "ddriverahn"
git config --global user.email "ddriverahn@ggg.com"

Generando tú public Key:
ssh-keygen

Leer dicha llave para copiarla en GitHub
cat ~/.ssh/id_rsa.pub 

Arrancando el proyecto
git init:		crea un nuevo repositorio(en el directorio que estamos ubicados)
touch:			Crear un nuevo archivo(README2)			
git add:		adiciona el archivo creado(README2)
git commit -m "Este el primer archivo desde mi computadora"
git remote add origin:  Trae los archivos a local desde la cuenta git(url de git)
git pull origin master: Prepara para llevar a cuenta git del ordenador todos los archivos locales
git push origin master:


git status:		estado del repositorio configurado

git@github.com:ddriverahn/clase-github.git

---------------------al haber un tipo de error----------------------
git fetch --all
git reset --hard origin/master
git checkout master