# Vila Solidária - Sistema de Gestão de Doações

## Sobre o Projeto
O sistema Vila Solidária é uma aplicação web desenvolvida para otimizar o gerenciamento de doações e o cadastro de famílias em situação de vulnerabilidade assistidas pela ONG localizada no bairro Jaburuna, em Vila Velha. O objetivo é substituir controles manuais por uma plataforma digital segura, responsiva e de fácil acesso.

## Estrutura do Repositório
* `/docs`: Contém a documentação do projeto (Documento de Visão).
* `/frontend`: Arquivos de interface de usuário (HTML, CSS, Bootstrap).
* `/backend`: Lógica de servidor e APIs (Node.js / Express).
* `/database`: Scripts de criação e modelagem do banco de dados (PostgreSQL).

## Instruções de Instalação (Ambiente de Desenvolvimento)
1. Clone este repositório: `git clone https://github.com/zyfalk/vila-solidaria.git`
2. Acesse a pasta do backend e instale as dependências: `npm install`
3. Copie o arquivo `.env.example` e renomeie para `.env`, preenchendo as variáveis de banco de dados.
4. Execute o servidor: `npm run dev`
