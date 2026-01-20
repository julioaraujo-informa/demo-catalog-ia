# 🤖 VS Code Agents Collection

Este repositório reúne uma coleção de **agents de IA para Visual Studio Code**, focados em **code review, qualidade de código e produtividade**.

Cada agent é um **arquivo independente**, que pode ser instalado ou configurado no VS Code conforme a extensão de IA utilizada (ex: GitHub Copilot, extensões de agents customizados, etc.).

---

## 📂 Agents Disponíveis

| Agent | Descrição | Instalação |
|------|----------|-----------|
| 🔍 **Code Review Agent** | Analisa código, sugere melhorias, identifica bugs e más práticas | [Instalar](./agents/code-review-agent.md) |

> ➕ Novos agents serão adicionados continuamente.

---

## 🧠 O que é um Agent?

Um agent é um **arquivo de configuração ou prompt** que orienta a IA a atuar com um objetivo específico, como:

- Revisar código
- Aplicar boas práticas
- Sugerir refatorações
- Validar padrões de projeto

---

## 🚀 Como usar os agents no VS Code

### Passo 1: Escolha o agent

Clique no link **Instalar** do agent desejado na tabela acima.

---

### Passo 2: Copie o conteúdo do agent

Abra o arquivo do agent no GitHub e copie todo o conteúdo.

---

### Passo 3: Crie o agent no VS Code

Dependendo da extensão utilizada, siga um dos caminhos abaixo:

#### 🔹 GitHub Copilot (Custom Instructions / Prompt)

1. Abra o **VS Code**
2. Pressione `Ctrl + Shift + P`
3. Procure por:
