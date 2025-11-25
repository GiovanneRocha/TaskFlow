# TaskFlow

![Badge](https://img.shields.io/badge/status-active-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

Gerenciador de tarefas colaborativo com autenticação, CRUD e dashboard interativo.

---

## 📌 Descrição
O **TaskFlow** é uma aplicação moderna para gerenciamento de tarefas, permitindo que usuários criem, editem e acompanhem suas atividades de forma simples e eficiente.

Inclui:
- Autenticação segura via **JWT**
- CRUD completo de tarefas
- Dashboard com estatísticas e gráficos
- Interface responsiva com **tema claro/escuro**

---

## 🛠 Tecnologias Utilizadas
### Backend
- Node.js
- Express.js
- MongoDB (Atlas)
- JWT para autenticação

### Frontend
- React + Vite
- TailwindCSS
- Axios para consumo da API
- Chart.js para gráficos

---

## 📂 Estrutura do Projeto
```
TaskFlow/
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── config/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
└── README.md
```

---

## 🚀 Como Rodar o Projeto
### Pré-requisitos
- Node.js instalado
- Conta no [MongoDB Atlas](https://www.mongodb.com/atlas/database)
- Gerenciador de pacotes (npm ou yarn)

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/taskflow.git
cd taskflow
```

### 2. Configuração do Backend
```bash
cd backend
npm install
```
Crie um arquivo `.env` com:
```
MONGO_URI=sua_string_de_conexao
JWT_SECRET=sua_chave_secreta
```
Inicie o servidor:
```bash
npm start
```

### 3. Configuração do Frontend
```bash
cd frontend
npm install
npm run dev
```
Acesse no navegador:
```
http://localhost:5173
```

---

## ✅ Funcionalidades
- Cadastro e login de usuários
- Criação, edição e exclusão de tarefas
- Dashboard com gráficos de progresso
- Interface responsiva e intuitiva

---

## 📦 O que está incluso
- Backend: Rotas, modelos e autenticação JWT
- Frontend: Páginas (Login, Dashboard, Tarefas) e integração com API
- Documentação: Este README completo

---

## 🔮 Próximos Passos
- Upload de arquivos nas tarefas
- Notificações em tempo real
- Integração com IA para sugestão de prioridades

---

## 📜 Licença
Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.
