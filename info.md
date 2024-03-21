# Configuración de SASS en package.json

A continuación se muestra el código necesario para configurar el compilador de SASS en un proyecto npm utilizando el archivo `package.json`.

```json
"scripts": {
  "sass": "sass --watch src/scss:build/css" //npm run sass
}

//npx gulp tarea