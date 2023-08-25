# Anotaciones JavaScript Avazando

## Trabajando con YARN

<https://classic.yarnpkg.com/en/>

```sh
npm i --global yarn 
```

## Verificar que tenga todo bien

```sh
yarn --version
```

## Trabajar con VITE

```sh
yarn create vite . # Para que se coloque en el directorio.
```

## Instalar la dependencias

```sh
yarn
```

## Levantar el servidor de desarrollo

```sh
yarn dev
```

## Subir al hosting, tengo que hacer un build
Para que me genere la carpeta de distribución. Con los archivos listos para subir al hosting.

```
yarn build
```

## Agregamos Bootstrap al proyecto

<https://getbootstrap.com/docs/5.3/getting-started/download/#package-managers>

```sh
yarn add bootstrap@5.3.1
yarn add bootstrap@latest
yarn add @popperjs/core
```

```sh
npm install bootstrap@latest
```

## Configurar Bootstrap

```main.js
import * as bootstrap from 'bootstrap'
```

```style.css
@import 'bootstrap' 
```