<div align="center">

  <!-- Animação de Digitação / Título -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Plus+Jakarta+Sans&weight=700&size=32&duration=3000&pause=1000&color=22C55E&center=true&vCenter=true&width=500&height=50&lines=🛒+MerceariaMVC;Gest%C3%A3o+Inteligente+e+Pr%C3%A1tica;ASP.NET+Core+MVC+%2B+EF+Core" alt="Typing SVG" />
  </a>

  <p align="center">
    <b>Plataforma web intuitiva e completa para controle de clientes, estoque e regras de negócio.</b>
  </p>

  <!-- Badges Tecnológicas -->
  <p align="center">
    <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
    <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
    <img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
    <img src="https://img.shields.io/badge/Entity%20Framework-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
    <br/>
    <img src="https://img.shields.io/badge/SQL%20Server-CC292B?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
    <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" />
  </p>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-db036000-a425-11eb-923d-791b32d239b0.gif" width="100%">

## 📌 Sumário

- [📖 Sobre o Projeto](#-sobre-o-projeto)
- [👨‍🎓 Autoria e Orientação](#-autoria-e-orientação)
- [🏗️ Estrutura da Arquitetura](#️-estrutura-da-arquitetura)
- [✨ Funcionalidades](#-funcionalidades)
- [📸 Capturas de Tela](#-capturas-de-tela)
- [🧪 Testes Unitários](#-testes-unitários)
- [🗄️ Script do Banco de Dados](#️-script-do-banco-de-dados)

---

## 📖 Sobre o Projeto

O **MerceariaMVC** é uma solução completa desenvolvida no padrão **MVC (Model-View-Controller)** para cadastro, manutenção e acompanhamento de **Clientes** e **Produtos**. 

Projetado com foco em usabilidade, o sistema conta com interface responsiva e moderna, validação de formulários no lado do servidor e persistência de dados relacional.

---

## 👨‍🎓 Autoria e Orientação

<div align="center">

| 👨‍💻 **Desenvolvedor / Aluno** | 👨‍🏫 **Professor / Orientador** |
| :---: | :---: |
| **Rodrigo Victor Damazio Costa Filho** | **Wallace Oliveira dos Santos** |
| 🎓 *Estudante de Desenvolvimento* | 📚 *Orientação Acadêmica* |

</div>

---

## 🏗️ Estrutura da Arquitetura

O projeto foi organizado separando responsabilidades no padrão MVC e incluindo testes automatizados:

```text
📂 MerceariaTests/
 ├── 📂 MerceariaMVC/          # Aplicação Principal (ASP.NET Core)
 │    ├── 📂 Controllers/       # Controladores de Clientes e Produtos
 │    ├── 📂 Models/            # Entidades e Regras de Negócio
 │    ├── 📂 Views/             # Interface de Usuário (Razor Pages)
 │    ├── 📂 Data/              # Contexto do Entity Framework
 │    └── 📂 imagens/           # Capturas de tela para documentação
 └── 📂 MerceariaMVCTests/      # Projeto de Testes Unitários
