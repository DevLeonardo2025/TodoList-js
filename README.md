# Proyecto de TodoList - Con JavaScript.

* Cuando clones el repositorio vuelve he instala los paquetes de node.

>>> npm install.

* Para correr el Proyecto local, con el siguiente comando.
>>> npm run dev

## Paquetes instalador para Pruebas.

* Jest - Paquete.

>>> npm install --save-dev jest

* Para activar los tipos en Jest.

>>> npm i @jest/types

* Para correr hacer pruebas en todos los componentes de Js.

>> npm install --save-dev babel-jest @babel/core @babel/preset-env

### Configurar el archivo babel.

* Creamos el archivo babel.config.cjs.

>>>module.exports = { presets: ['@babel/preset-env', {targets: {node: 'current'}}]}