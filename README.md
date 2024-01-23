# FullSatck---NodeMYSQL

# Node.js Aplicação Passo a Passo

Este é um guia passo a passo para configurar e executar uma aplicação Node.js que utiliza as seguintes dependências:

- [cors](https://www.npmjs.com/package/cors) (^2.8.5)
- [ejs](https://www.npmjs.com/package/ejs) (^3.1.9)
- [express](https://www.npmjs.com/package/express) (^4.18.2)
- [knex](https://www.npmjs.com/package/knex) (^3.1.0)
- [method-override](https://www.npmjs.com/package/method-override) (^3.0.0)
- [mysql2](https://www.npmjs.com/package/mysql2) (^3.7.0)

## Pré-requisitos

Certifique-se de ter o Node.js e o npm instalados em seu sistema. Você pode baixá-los em [https://nodejs.org/](https://nodejs.org/).

## Instalação

1. Clone este repositório para o seu ambiente local.

   ```bash
   git clone https://github.com/seu-usuario/sua-aplicacao.git
   ```

2. Navegue até o diretório do projeto.

   ```bash
   cd sua-aplicacao
   ```

3. Instale as dependências usando o npm.

   ```bash
   npm install
   ```

## Configuração do Banco de Dados

1. Certifique-se de ter um servidor MySQL em execução em sua máquina ou defina as configurações do banco de dados no arquivo `knexfile.js` na raiz do projeto.

2. Execute as migrações para criar as tabelas do banco de dados.

   ```bash
   npx knex migrate:latest
   ```

## Execução

1. Inicie o servidor de desenvolvimento com [nodemon](https://www.npmjs.com/package/nodemon).

   ```bash
   npm run dev
   ```

   Isso iniciará o servidor na porta padrão 3000, mas você pode acessá-lo em [http://localhost:3000/](http://localhost:3000/).

2. A aplicação agora está pronta para uso. Você pode explorar os diferentes endpoints API e personalizar conforme necessário.

## Desenvolvimento

Durante o desenvolvimento, você pode usar o nodemon para reiniciar automaticamente o servidor sempre que houver alterações no código.

```bash
npm run dev
```



