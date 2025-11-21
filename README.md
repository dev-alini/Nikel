Nikel — Aplicação de Controle Financeiro

O Nikel é uma aplicação web de controle financeiro pessoal que permite ao usuário registrar entradas e saídas, visualizar saldo total, organizar transações e manter seus dados de forma simples e intuitiva utilizando HTML, CSS, JavaScript e LocalStorage.

Este projeto foi inspirado em boas práticas de UI/UX, arquitetura limpa no front-end e padrões de manipulação de dados no navegador.

📌 Funcionalidades
🔐 Autenticação

Login baseado em LocalStorage.

Criar conta com validações de segurança.

Sessão persistente opcional ("Permanecer logado").

Redirecionamentos automáticos conforme estado de login.

💰 Home — Dashboard Financeiro

Exibição do total em caixa (Entradas - Saídas).

Listagem prévia dos últimos lançamentos.

Exibição separada de:

Entradas (Cash In)

Saídas (Cash Out)

Botão flutuante para adicionar novos lançamentos.

🧾 Tela de Lançamentos

Tabela completa com todos os registros.

Modal para adicionar novos lançamentos.

Campos:

Valor

Descrição

Data

Tipo (Entrada / Saída)

💾 Persistência de Dados

Todos os dados são salvos por usuário no LocalStorage.

Estrutura:
{
  "login": "email@example.com",
  "password": "1234",
  "transactions": [
    { "value": 100, "description": "Salário", "date": "2024-11-01", "type": 1 }
  ]
}
🛠️ Tecnologias Utilizadas
Tecnologia	Uso
HTML5	Estrutura das páginas
CSS3 + Bootstrap 5	Estilização responsiva
JavaScript	Lógica principal da aplicação
Bootstrap Icons	Ícones
LocalStorage / SessionStorage	Persistência dos dados

/
│── index.html
│── home.html
│── transactions.html
│
│── css/
│   └── styles.css
│
│── js/
│   ├── index.js
│   ├── home.js
│   └── transaction.js
│
│── assets/
│   ├── nikel-logo.png
│   ├── coins.png
│   ├── coins-small.png
│   ├── pocket.png
│   └── ...
│
└── README.md


