# 🚗 Sistema de Concessionária — Aplicação CRUD em PHP e MySQL

Este repositório contém um sistema web desenvolvido para o gerenciamento operacional de uma concessionária, permitindo o controle completo dos dados de **clientes**, **funcionários**, **marcas**, **modelos** e **vendas**.  
A aplicação foi construída utilizando **PHP**, **MySQL** e **Bootstrap**, e executada em ambiente local através do **XAMPP**.

---

## 🧰 Tecnologias Utilizadas

- **PHP** — Linguagem responsável pelo processamento das regras de negócio.  
- **MySQL** — Banco de dados relacional utilizado para armazenamento estruturado das informações.  
- **HTML / CSS / JavaScript** — Camada de apresentação e interação com o usuário.  
- **Bootstrap** — Framework voltado para a criação de interfaces responsivas.  
- **XAMPP** — Ambiente local contendo Apache e MySQL para execução do projeto.

---

## 🚀 Funcionalidades do Sistema

- ✔ Cadastro, consulta, edição e exclusão de **clientes**  
- ✔ Cadastro, consulta, edição e exclusão de **funcionários**  
- ✔ Gerenciamento de **marcas** de veículos  
- ✔ Gerenciamento de **modelos** vinculados às marcas  
- ✔ Registro e consulta de **vendas**  
- ✔ Integração completa com o banco de dados MySQL  
- ✔ Interface simples, organizada e de fácil navegação  

---

## 🧠 Conceitos Aplicados

- **CRUD (Create, Read, Update, Delete)** aplicado a todas as entidades do sistema  
- Comunicação e operações de banco de dados através de **mysqli**  
- Arquitetura modular com separação entre listagens, cadastros e ações de edição  
- Utilização de formulários HTML com métodos **POST** e **GET**  
- Organização das páginas conforme a responsabilidade funcional de cada módulo  

---

## 🛠 Guia de Instalação e Execução

1. **Instale o XAMPP**  
   Certifique-se de ativar os serviços **Apache** e **MySQL** no painel de controle.

2. **Copie o projeto** para o diretório raiz do servidor local:  
   text
   C:\xampp\htdocs\concessionaria
`

3. **Acesse o MySQL** pelo phpMyAdmin ou pelo terminal do XAMPP.

4. **Crie o banco de dados** utilizando o mesmo nome configurado no arquivo `config.php`:

   sql
   CREATE DATABASE concessionaria;
   USE concessionaria;
   

5. **Importe o arquivo SQL** fornecido junto ao projeto:
   No terminal do XAMPP (Shell), execute:

   text
   SOURCE C:/xampp/htdocs/concessionaria/banco.sql;
   

6. **Execute o sistema no navegador** acessando:
   👉 [http://localhost/concessionaria/index.php](http://localhost/concessionaria/index.php)


Se quiser, posso adicionar *badges, imagens, screenshots, diagrama ER*, ou deixar o README no estilo “GitHub profissional” com seções avançadas. Quer que eu adicione mais algum detalhe```
