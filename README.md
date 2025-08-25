# Projeto Eventos Plus

## Projeto desenvolvido durante a UC 4 - Publicar aplicações web

# 🎉 Eventos Plus

**Eventos Plus** é um site institucional desenvolvido para gerenciamento e divulgação de eventos, utilizando uma stack moderna baseada em **Node.js**, **HTML**, **CSS**, **JavaScript**, e banco de dados relacional com **Knex.js**.

---

## 🚀 Tecnologias Utilizadas

- **Node.js** – Backend com JavaScript
- **Express.js** – Framework de aplicações web
- **Knex.js** – Query builder SQL para Node.js
- **HTML5** – Estruturação da interface
- **CSS3 / Biblioteca de Estilização** – Estilo moderno e responsivo
- **JavaScript (Vanilla)** – Interatividade no frontend

---

## 📁 Estrutura do Projeto

```plaintext
eventos-plus/
│
├── controllers/         # Lógica de controle das rotas
│   └── eventosController.js
│
├── views/               # Páginas HTML renderizadas
│   ├── index.html
│   ├── eventos.html
│   └── contato.html
│
├── public/              # Arquivos públicos (CSS, JS, imagens)
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
│
├── database/            # Configuração do banco de dados com Knex
│   ├── knexfile.js
│   └── migrations/
│
├── routes/              # Definições de rotas da aplicação
│   └── eventosRoutes.js
│
├── .env                 # Variáveis de ambiente
├── package.json         # Dependências e scripts do projeto
└── server.js            # Arquivo principal do servidor
