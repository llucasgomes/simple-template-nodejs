## estruturas de pastas

src => Onde vai ficar todo o codigo back-end (pasta mae)
 |--core => Regras de Negocio, funcoes inportantes..
 |--  calc.ts
 |--  pdf.ts
 |--  conversao.ts
 |--controllers => Controllers da aplicação
 |--- users.controller.ts
 |--routes => 
 |--services => Lidar com servicos de terceiros (apis)
 |--- maps.service.ts
 |--app => Configuraçoes da aplicação,tudo que é config para que a aplicação funcione
 |--- app.json = { "version":"1.0","name":"app-algumacoisa"}
 |--database => Tudo relacionado a Banco de Dados (config, entidades,models...)
 |
server.js => Arquivo (Servidor) na pasta raiz

## 4 Libs importantes a serem instaladas

Build
yarn add tsup --dev

Executar Ts sem precisar converter
yarn add tsx --dev

Testes     => yarn add vitest --dev 
Validações => yarn add zod  

## Instalar Typescript

yarn add typescript --dev

## Instalar Eslint Rockeatseat

yarn add --dev eslint @rocketseat/eslint-config
Inside ".eslintrc.json" na raiz do projeto:
{
  "extends": "@rocketseat/eslint-config/node"
}
