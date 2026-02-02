# 🖼️ Projeto Galeria de Imagens

O **Projeto Galeria de Imagens** é uma aplicação **Full Stack** desenvolvida para demonstrar **boas práticas de arquitetura, organização de código e separação de responsabilidades** entre **Frontend, Backend, Banco de Dados e Infraestrutura**.

O projeto foi pensado para ser **escalável, modular e preparado para produção**, ideal para **estudos avançados** e **portfólio profissional**.

---

## 🚀 Funcionalidades

- 📸 Upload e exibição de imagens  
- 🗂️ Galeria organizada e responsiva  
- 🌐 Comunicação via API REST  
- 🧩 Componentização e reutilização de templates  
- 📦 Build otimizado com Webpack  
- 🐳 Ambiente containerizado  
- ⚡ Estrutura pronta para deploy  

---

## 🧰 Stacks e Tecnologias Utilizadas

### 🎨 Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)

---

### 📦 Build & Bundler
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)

---

### 🌐 Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge)

---

### 🗄️ Banco de Dados
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

---

### ⚙️ Infraestrutura & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-0db7ed?style=for-the-badge)

- Containerização da aplicação  
- Orquestração de múltiplos serviços  
- Padronização de ambiente  
- Separação de ambientes (dev / prod)  
- Base preparada para CI/CD e deploy em cloud  

---

## 📂 Estrutura do Projeto

projeto-galeria/
│
├── backend/
│ ├── src/
│ │ ├── controllers/
│ │ ├── routes/
│ │ ├── services/
│ │ └── app.ts
│ ├── Dockerfile
│ └── package.json
│
├── frontend/
│ ├── src/
│ │ ├── js/
│ │ ├── styles/
│ │ └── templates/
│ ├── build/
│ │ ├── imgs/
│ │ ├── bundle.js
│ │ └── index.html
│ ├── webpack.config.js
│ └── package.json
│
├── docker-compose.yml
├── .gitignore
└── README.md

yaml

---

## ▶️ Como Executar o Projeto

### 🐳 Executar com Docker
```bash
docker-compose up --build
💻 Executar Manualmente
Backend
bash
Copiar código
cd backend
npm install
npm run dev
Frontend
bash
Copiar código
cd frontend
npm install
npm run build
Abra no navegador:

bash
Copiar código
frontend/build/index.html
🎯 Objetivo do Projeto
Demonstrar conhecimento Full Stack

Aplicar arquitetura organizada e escalável

Utilizar API REST

Trabalhar com Docker e Docker Compose

Servir como projeto de portfólio profissional

🔮 Evoluções Futuras
🔐 Autenticação JWT

☁️ Upload de imagens em cloud

⚛️ Migração para React ou Vue

📊 Dashboard administrativo

🚀 Pipeline CI/CD

👨‍💻 Autor
Desenvolvido por Diego Hugo

⭐ Se este projeto te ajudou ou inspirou, deixe uma estrela no repositório!
