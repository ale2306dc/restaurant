# Restaurant

_Necesario instalar Node.js_

## Pasos a Seguir:

1. Dirigirnos a la terminal de _VS Code_ (ctrl+ñ o ctrl+`)

2. Vamos a instalar las dependencias necesarias:

    - Inicializamos nuestro proyecto con el comando __npm init__

    - Empezaremos a ver una serie de campos, como el nombre del paquete, el autor, la version, e incluso podemos agregar una descripción a nuestro archivo. Sin embargo, esto puede ser configurado después dentro del archivor resultante (package.json)

    - Una vez hecho esto, instalaremos *json_server*, para esto utilizaremos el comando __npm i json_server__

3. Vamos a agregar el script necesario para iniciar nuestro servidor:

    - En el archivo _package.json_ vamos a agregar un script llamado __server__

        - __ACLARACIÓN__: El nombre del script es irrelevante, puede llamarse de cualquier forma
    
    - Agregamos el script escribiendo __"server": "json-server --watch db.json"__

4. Volvemos a la terminal y colocamos el comando __npm run server__

Listo, el servidor ya está corriendo!






