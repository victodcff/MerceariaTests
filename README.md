# 🛒 MerceariaMVC

Uma aplicação web para gerenciamento de clientes e estoque de produtos para mercearias, desenvolvida no padrão de arquitetura **MVC (Model-View-Controller)** com **ASP.NET Core**.

---

## 📌 Sumário

- [Sobre o Projeto](#-sobre-o-projeto)
- [✨ Funcionalidades](#-funcionalidades)
- [🛠️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [📸 Capturas de Tela](#-capturas-de-tela)
- [🚀 Como Executar o Projeto](#-como-executar-o-projeto)
- [🗄️ Script do Banco de Dados](#️-script-do-banco-de-dados)
- [✒️ Autor](#️-autor)

---

## 📖 Sobre o Projeto

O **MerceariaMVC** é uma solução completa para cadastro e controle de **Clientes** e **Produtos**. O sistema conta com uma interface moderna e intuitiva no estilo *Clean/Minimalista*, permitindo cadastrar, listar, editar e remover registros (CRUD completo), além de validar regras de negócio no servidor.

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

## 🛠️ Tecnologias Utilizadas

### **Back-end**
- **C#** (.NET)
- **ASP.NET Core MVC**
- **Entity Framework Core** (ORM)

### **Front-end**
- **HTML5** / **CSS3**
- **Bootstrap 5** (Layout moderno e responsivo)
- **Bootstrap Icons** (Ícones visuais)
- **Razor Views** (`.cshtml`)

### **Banco de Dados**
- **SQL Server** / **LocalDB**

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

## 🚀 Como Executar o Projeto

### 📋 Pré-requisitos
- [.NET SDK](https://dotnet.microsoft.com/download)
- [Visual Studio](https://visualstudio.microsoft.com/) ou [VS Code](https://code.visualstudio.com/)
- [SQL Server](https://www.microsoft.com/sql-server/) ou LocalDB

### 🔧 Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/SEU_USUARIO/MerceariaMVC.git](https://github.com/SEU_USUARIO/MerceariaMVC.git)
   cd MerceariaMVC
