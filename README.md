# SimuTCWeb

Sitio estático del simulador de Turismo Carretera preparado para ejecutarse con un servidor Node.js sin dependencias externas.

## Requisitos

- [Node.js](https://nodejs.org/) 18 o superior

## Uso

```bash
npm start
```

El servidor quedará escuchando por defecto en `http://localhost:3000`. Se puede modificar el puerto mediante la variable de entorno `PORT`.

```bash
PORT=8080 npm start
```

## Estructura

- `server.js`: servidor HTTP básico que sirve los archivos estáticos.
- `public/index.html`: archivo estático original.
- `package.json`: script de ejecución.
