# 0_node-typescript-setup

* init project => `npm init -y`

* install typescript => `yarn add -D @types/node typescript`

* add tsconfig.json => `npx tsconfig.json` => choose node option

## TS-NODE vs COMPILAR PRIMERO Y LUEGO USAR NODEMON

* install ts-node => `yarn add -D ts-node` => En principio no se usa, se compila primero a js con `tsc` y luego se usa `node dist/index.js` con nodemon

* add nodemon => `yarn add -D nodemon`
