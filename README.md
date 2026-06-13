<!--
  TEMPLATE: Academic Work
  Use para: trabalhos de graduação (ESTACIO), atividades extensionistas
-->

# Sistema de Agendamentos para Academia Comunitária

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-GUI-007396?style=flat)
![Maven](https://img.shields.io/badge/Maven-3.x-C71A36?style=flat&logo=apachemaven&logoColor=white)
![Estácio](https://img.shields.io/badge/Estácio-4º%20Semestre-0047AB?style=flat)
![ADS](https://img.shields.io/badge/ADS-POO-2E8B57?style=flat)

> Sistema de agendamentos para academia comunitária com interface gráfica em Java Swing. Atividade avaliativa da disciplina de Programação Orientada a Objetos — 4º semestre de Análise e Desenvolvimento de Sistemas na Universidade Estácio de Sá.

---

## 🎯 Contexto Acadêmico

| Item | Detalhe |
|------|---------|
| **Instituição** | Universidade Estácio de Sá |
| **Curso** | Análise e Desenvolvimento de Sistemas |
| **Disciplina** | Programação Orientada a Objetos (POO) |
| **Semestre** | 4º semestre |
| **Ano** | 2024 |

---

## 📋 Objetivo

Desenvolver um sistema desktop em Java que permita o gerenciamento de agendamentos para uma academia comunitária. O sistema deve oferecer autenticação de usuários, cadastro de horários para agendamento e visualização dos agendamentos realizados, aplicando os conceitos de Programação Orientada a Objetos, interfaces gráficas com Swing e persistência de dados em arquivo.

---

## 🛠️ Tecnologias Utilizadas

- **Java** — Linguagem principal, com suporte a JDK 8+
- **Java Swing** — Interface gráfica desktop (GUI)
- **Maven** — Gerenciamento de dependências e build
- **Persistência em arquivo** — Armazenamento de agendamentos em `agendamentos.txt`

---

## ⚙️ Como Executar

```bash
# Clone o repositório
git clone https://github.com/silviorodrigues98/java_graduacao_ESTACIO.git
cd java_graduacao_ESTACIO

# Compile com Maven
./mvnw compile

# Execute
./mvnw exec:java -Dexec.mainClass="App"
```

> **Alternativa:** Importe o projeto como um projeto Maven em sua IDE (Eclipse, IntelliJ IDEA) e execute a classe `App`.

---

## 📚 Conceitos Aplicados

- **Programação Orientada a Objetos** — Classes, métodos, encapsulamento e organização do código
- **Interface Gráfica com Swing** — Construção de janelas, botões, campos de texto e painéis interativos
- **Persistência de Dados** — Leitura e escrita de agendamentos em arquivo texto (`agendamentos.txt`)
- **Controle de Fluxo** — Navegação entre telas (Login → Tela Principal → Cadastro / Visualização)
- **Autenticação Simples** — Validação de credenciais fixas para acesso ao sistema

---

<p align="center">
  Projeto acadêmico desenvolvido para a disciplina de Programação Orientada a Objetos — 4º semestre de Análise e Desenvolvimento de Sistemas
</p>

<p align="center">
  <a href="https://github.com/silviorodrigues98">@silviorodrigues98</a>
</p>
