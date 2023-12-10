# Base de datos no relacional

Necesitan instalar mongoBD, yo instale MongoDB Community Server https://www.mongodb.com/try/download/community Y
las herramientas MongoDB Shell y MongoDB Compass (GUI) del apartado Tools

Para poder crear y poblar la base de datos se debe:
1. abrir la cmd desde la carpeta que tenga los archivo, en este caso, la carpeta lab3_TBD_grupo3
2. (solo una vez) instalar el controlador de mongodb con el comando `npm install mongodb` (ejecuta los archivos js con la base de datos 'TBD_Lab3')
3. ejecutar el comando `node dbCreate.js` para crear la base de datos
4. ejecutar el comando `node dataImport.js` para poblar la base de datos

Podrás ver el resultado en MongoDB Compass


