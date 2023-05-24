# Delibot instalador
Repo para actualizar la aplicación de delibot


## Versiones
Deben de confrimar que la versión del package.json coincida con la de la release 


## Installation

Deben de verificar que tengan instalado electron-builder en las DEV dependencies 
```bash
  npm install electron-builder --save-dev 
```

Antes de correr el siguiente comando debes de borrar la carpeta dist del proyecto

Correr el comando para compilar el instalador con: 
```bash
  npm run dist
```
Una vez creado el instalador borrar TODOS los espacios y sustituirlos por guiones "-"
## Crear realese en github

- Poner como título el número de la nueva versión

- Agregar como tag igualmente el número de la versión

- Subir los archivos: builder-debug, builder-effective-confi, delibot setup, delibot setup.exe.blockmap y latest. NO INCLUIR EL WIN-UNPACKED.

y listo, la nueva actualización está subida y lista para su descarga.