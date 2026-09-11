# 🛒 MerceariaMVC

Uma aplicação web para gerenciamento de clientes e estoque de produtos para mercearias, desenvolvida no padrão de arquitetura **MVC (Model-View-Controller)** com **ASP.NET Core**.

---

## 🛠️ Tecnologias Utilizadas

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

---

## 📌 Sumário

- [Sobre o Projeto](#-sobre-o-projeto)
- [👨‍🎓 Autoria e Orientação](#-autoria-e-orientação)
- [✨ Funcionalidades](#-funcionalidades)
- [📸 Capturas de Tela](#-capturas-de-tela)
- [🗄️ Script do Banco de Dados](#️-script-do-banco-de-dados)

---

## 📖 Sobre o Projeto

O **MerceariaMVC** é uma solução para cadastro e controle de **Clientes** e **Produtos**. O sistema conta com uma interface moderna e intuitiva, permitindo cadastrar, listar, editar e remover registros (CRUD completo), além de validar regras de negócio diretamente no servidor.

---

## 👨‍🎓 Autoria e Orientação

- **Aluno / Desenvolvedor:** Rodrigo Victor Damazio Costa Filho
- **Professor / Orientador:** Wallace Oliveira dos Santos

---

## ✨ Funcionalidades

### 👥 Módulo de Clientes
- Cadastro de novos clientes com validações (nome, e-mail e idade).
- Controle de status (Ativo / Inativo).
- Regra de negócio: verificação de maioridade (18+ anos) e permissão para compra.
- Listagem, edição e exclusão de registros.

### 📦 Módulo de Produtos
- Cadastro de produtos informando nome, preço e quantidade em estoque.
- Validação automática de regras de negócio (preço e estoque maiores que zero).
- Edição, atualização de estoque e remoção de registros.

---

## 📸 Capturas de Tela

### 🏠 Painel Inicial (Home)
![Página Inicial](imagens/home.png)

---

### 📍 Módulos do Sistema

| Gestão de Clientes | Gestão de Produtos |
| :---: | :---: |
| ![Módulo de Clientes](imagens/clientes.png) | ![Módulo de Produtos](imagens/produtos.png) |

---

## 🗄️ Script do Banco de Dados

Caso queira popular o banco diretamente com dados de teste:

```sql
-- Inserir Clientes
INSERT INTO Clientes (Nome, Email, Idade, Ativo) VALUES 
('Ana Silva', 'ana.silva@email.com', 28, 1),
('Carlos Eduardo', 'carlos.eduardo@email.com', 35, 1),
('Mariana Oliveira', 'mariana.oliveira@email.com', 22, 1);

-- Inserir Produtos
INSERT INTO Produtos (Nome, Preco, Estoque) VALUES 
('Arroz Agulhinha 5kg', 24.90, 50),
('Feijão Carioca 1kg', 8.50, 80),
('Café Torrado 500g', 16.90, 35);
