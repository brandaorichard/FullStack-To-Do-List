<h1>📌 To-Do List (MERN Stack)</h1>

<p>Este repositório contém a aplicação To-Do List, desenvolvida com MongoDB, Express, React e Node.js (MERN Stack).</p>

<h2>🚀 Tecnologias Utilizadas</h2>

Node.js - Ambiente de execução JavaScript

Express.js - Framework minimalista para Node.js

MongoDB - Banco de dados NoSQL

Mongoose - ODM para modelagem de dados

React.js - Biblioteca para construção da interface do usuário

TypeScript - Tipagem estática para JavaScript

Chakra UI - Biblioteca de componentes estilizados para React

Dotenv - Gerenciamento de variáveis de ambiente

ESLint - Linter para garantir qualidade do código

Prettier - Formatação automática do código


<h2>🖥️ Backend</h2> 

<h3>📂 Estrutura do Projeto</h3>
```
fullstack-todolist/
│-- backend/
│   ├── config/
│   │   ├── db.js        # Configuração da conexão com MongoDB
│   ├── models/
│   │   ├── Task.js      # Modelo de dados da Tarefa
│   ├── routes/
│   │   ├── taskRoutes.js # Rotas da API para gerenciar tarefas
│   ├── server.js        # Configuração e inicialização do servidor Express
│   ├── .env             # Variáveis de ambiente (não versionado)
│   ├── .gitignore       # Ignora arquivos desnecessários no Git
│   ├── package.json     # Dependências e scripts do projeto
│   ├── eslint.config.js # Configuração do ESLint
```
🔌 Configuração do Ambiente

1️⃣ Clone o repositório
```
git clone https://github.com/seu-usuario/fullstack-todolist.git
cd fullstack-todolist/backend
```
2️⃣ Instale as dependências
```
npm intall
```
3️⃣ Configure as variáveis de ambiente

Crie um arquivo .env na pasta backend/ e adicione:
```
MONGO_URI=mongodb://localhost:27017/todolist
PORT=5000
```
4️⃣ Inicie o servidor
```
npm run dev
```
O backend será executado em http://localhost:5000.
































