# Crud-Next.js
Este é um projeto de exemplo que demonstra um CRUD básico (Create, Read, Update, Delete) usando Next.js. Ele utiliza a tecnologia de banco de dados MongoDB para armazenar os dados.
<a href="https://crud-next-js-seven.vercel.app/"> Acesse Aqui</a>

<img src="https://media1.giphy.com/media/MAnSlDfcRbjPaSF9Ub/giphy.gif?cid=790b761126b89eb176f3c3278bf053a285c23dee808c1ede&rid=giphy.gif&ct=g"/>

## Funcionalidades

- Criação de novos registros
- Leitura de registros existentes
- Atualização de registros
- Exclusão de registros

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter as seguintes ferramentas instaladas em seu ambiente de desenvolvimento:

- Node.js (v12 ou superior)
- MongoDB (certifique-se de ter um servidor MongoDB em execução)

## Instalação

1. Faça um clone deste repositório para o seu ambiente local.
2. Navegue até o diretório raiz do projeto.
3. Execute o seguinte comando para instalar as dependências do projeto:
```javascript
npm install
```

## Configuração

Antes de executar o projeto, é necessário configurar a conexão com o banco de dados MongoDB. Siga as etapas abaixo para configurar as variáveis de ambiente:

1. Crie um arquivo `.env.local` no diretório raiz do projeto.
2. Abra o arquivo `.env.local` e adicione as seguintes linhas:
```
MONGODB_URI=<sua_url_do_mongodb>
```

Substitua `<sua_url_do_mongodb>` pela URL de conexão do seu servidor MongoDB.

## Execução

Após concluir a instalação e a configuração, você pode iniciar o servidor de desenvolvimento executando o seguinte comando:
```javascript
npm run dev
```

O servidor será iniciado na porta `3000`. Acesse `http://localhost:3000` no seu navegador para visualizar o projeto.

## Contribuição

Sinta-se à vontade para contribuir para o projeto fazendo um fork e enviando pull requests. Ficarei feliz em revisar e mesclar as alterações.





