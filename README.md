# 🚀 Jornada Django 4: Do Zero ao Servidor Local

Este repositório registra os primeiros passos e fundamentos aprendidos durante o desenvolvimento com o framework **Django 4**.

---

## 📌 Visão Geral da Aula

Nesta etapa inicial, foram explorados os conceitos essenciais para configurar um ambiente profissional de desenvolvimento em Python, inicializar a estrutura básica de um projeto Django e executar o servidor local.

---

## 🗺️ Roadmap de Aprendizado

### 1. Fundamentos do Django 4
- **História e Propósito:** Compreensão do surgimento do Django, sua evolução até o Django 4 e o foco no desenvolvimento ágil e limpo.
- **Filosofia "Batteries Included":** O framework já entrega recursos essenciais prontos de fábrica (ORM, autenticação, painel administrativo, segurança contra CSRF/SQL Injection).
- **Padrão Arquitetural (MTV):** Introdução ao padrão *Model-Template-View*, que rege a organização de dados, interface e regras de negócio no Django.

---

### 2. Configuração do Ambiente Virtual (`virtualenv`)
- **Isolamento de dependências:** Garantia de que as bibliotecas instaladas não entrem em conflito com a instalação global do sistema operacional.
- **Fluxo de trabalho:**
  ```powershell
  # Instalação do gerenciador (se necessário)
  pip install virtualenv

  # Criação do ambiente virtual
  virtualenv venv

  # Ativação no Windows (PowerShell)
  .\venv\Scripts\Activate.ps1

  # Instalação do Django
  pip install django