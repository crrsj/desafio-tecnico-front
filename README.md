
Frontend - Sistema de Gerenciamento
📋 Sobre o Projeto
Interface web para gerenciamento de projetos e tarefas, desenvolvida para consumir a API REST em Java Spring Boot.

🚀 Tecnologias
HTML5

CSS3

JavaScript (ES6+)

Bootstrap 5.3

Font Awesome 6.4

🎨 Características

Design Responsivo - Adaptável para desktop, tablet e mobile

Tema Azul e Branco - Interface clean e profissional

Single Page Application - Navegação sem recarregamento

Validação de Formulários - Feedback em tempo real

Paginação - Para listas extensas

Modais - Para criação e edição

Tratamento de Erros - Mensagens amigáveis

📱 Funcionalidades

👥 Gerenciamento de Projetos

✅ Listar projetos com paginação

✅ Criar novos projetos

✅ Editar projetos existentes

✅ Excluir projetos com confirmação

✅ Buscar projeto por ID

✅ Gerenciamento de Tarefas
✅ Listar tarefas com paginação

✅ Criar novas tarefas vinculadas a projetos

✅ Editar tarefas existentes

✅ Excluir tarefas com confirmação

✅ Filtros por status e prioridade

✅ Badges coloridas para status e prioridade

🎯 Estrutura de Arquivos
text
frontend/
├── index.html          # Arquivo principal
├── (embutido)          # CSS e JavaScript inline
└── assets/             # (Opcional) Imagens e ícones
⚙️ Configuração
Pré-requisitos
Navegador moderno (Chrome, Firefox, Edge)

Servidor web simples (opcional)

API Backend rodando na porta 8080

🔌 Integração com API
URL Base
javascript
const API_BASE_URL = 'http://localhost:8080';
Endpoints Consumidos
GET /projects - Listar projetos

POST /projects - Criar projeto

PUT /projects/{id} - Atualizar projeto

DELETE /projects/{id} - Excluir projeto

GET /tasks - Listar tarefas

POST /tasks/{projectId} - Criar tarefa

PUT /tasks/{id} - Atualizar tarefa

DELETE /tasks/{id} - Excluir tarefa

🎨 Personalização
Cores do Tema
Primária: Azul (#2563eb)

Secundária: Azul escuro (#1e40af)

Fundo: Branco (#ffffff)

Texto: Cinza escuro (#1e293b)

Componentes
Navbar fixa com logo e menu

Sidebar com navegação entre seções

Cards para organização de conteúdo

Modais para formulários

Tabelas responsivas com ações

Badges coloridas para status

📱 Responsividade
Desktop: Layout completo com sidebar

Tablet: Layout adaptado

Mobile: Menu hamburger e cards empilhados

🔧 Funcionalidades Técnicas
JavaScript
Fetch API para comunicação REST

Manipulação DOM dinâmica

Formatação de datas

Tratamento de erros

Paginação client-side

UX/UI
Loading states durante requisições

Mensagens de sucesso/erro

Confirmação para exclusões

Formulários com validação

Feedback visual para ações

![desafio3](https://github.com/user-attachments/assets/8b6eb284-08f7-4f57-aa85-fb0f6370f044)
![desafio4](https://github.com/user-attachments/assets/685cce80-68b6-43f8-9ed6-8044a9a04ae5)



