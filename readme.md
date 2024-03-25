El archivo lo he ubicado en: pepey\OneDrive\Documents\LeemonCode\proyectoabc
*Al abrir la terminal, me ubica en pepey. Para ingresar a la campeta LeemonCode, que es donde voy a crear la carpeta del proyecto, 
utilizo el comando cd ./"nombre de la carpeta" para ir avanzando. los comandos que utilicé fueron: 
cd ./OneDrive | cd ./Documents | cd ./LeemonCode 

*Para crear la carpeta "proyectoabd" desde el terminal use mkdir proyectoabd.

*Para inicial el repositorio de git: - git init

*Para crear un nuevo repositorio, me voy a mi perfil en github, entro en el apartado repositorios y hago click en "Nuevo". Nombre al repositorio "proyectoabc" y le di a crear directorio.

*Para conectar el repositorio local con el repositorio de GitHub, primero hago git add . para añadir los cambios, git commit -m "primer commit". Después usé
git remote add origin git@github.com:StrachanG/proyectoabc.git para conectar con el repositorio en GitHub, y git push -u origin master para subir el archivo readme.md
al respositorio de GitHub.

*El siguiente paso es crear un archivo nuevo en la carpeta del repositorio, para ello voy a crear un archivo html "index.html" que va a contener un div que contenga un H1 con el texto "Hola mundo!", y un css llamado "style.css" que centrará este h1 en la pantalla, y le establecerá un color de texto degradado.

*Para añadir el archivo al staging me dirijo al apartado "source control" en Visual Studio Code. Como commit descriptivo añado "primer commit" y seguidamente pulso el "push".

*Para crear una nueva rama llamada "development" pongo el comando git branch "development". Y para cambiar a esta rama - git checkout development.

*Los cambios realizados en la rama development ha sido en el archivo index.html - En lugar de "Hola mundo!" ahora pone "Hello World!"