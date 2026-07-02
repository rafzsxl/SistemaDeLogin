# 🔐 Sistema de Login — Timão Edition

<p align="center">
  <img src="https://img.shields.io/github/repo-size/rafzsxl/SistemaDeLogin?style=for-the-badge" alt="Repo Size">
  <img src="https://img.shields.io/github/languages/top/rafzsxl/SistemaDeLogin?style=for-the-badge" alt="Top Language">
</p>

## 📝 Descrição
Este projeto é um sistema de login simples, dinâmico e direto, desenvolvido utilizando o micro-framework **Flask (Python)** no backend e **HTML5/CSS3** no frontend. A interface possui uma identidade visual personalizada e temática em homenagem ao Corinthians campeão da Libertadores de 2012, contando com um formulário translúcido no estilo *Glassmorphism*.

## 🚀 Funcionalidades
- [x] **Autenticação Backend:** Processamento seguro e validação de credenciais via método `POST` usando Python.
- [x] **Interface Temática:** Plano de fundo estilizado com imagem histórica do Timão e títulos em dourado (`gold`).
- [x] **Design Centralizado:** Layout perfeitamente alinhado ao centro da tela utilizando CSS Flexbox (`100vh`).
- [x] **Estrutura Padrão Flask:** Separação organizada de arquivos estáticos (`static/`) e visões dinâmicas (`templates/`).

## 🛠️ Tecnologias Utilizadas
- **Python 3**
- **Flask** (Micro-framework web para backend)
- **HTML5** (Estruturação semântica)
- **CSS3** (Estilização, transparências `rgba` e layouts flexíveis)

## 📂 Estrutura de Pastas
Para que o servidor Flask localize corretamente os arquivos, o repositório segue a estrutura padrão:
```text
├── static/
│   └── style.css       # Estilização e design do formulário
├── templates/
│   └── index.html      # Estrutura HTML do formulário de login
└── app.py              # Código principal do servidor Flask
