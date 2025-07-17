# 🎯 Projetos em JavaScript e React Native

Este repositório contém dois projetos simples com finalidades diferentes:

1. 🕹️ **Jogo da Forca (HTML + JavaScript + Canvas)**
2. ✅ **App de Gerenciamento de Tarefas (React Native)**

Cada projeto tem foco em praticar lógica, estrutura de dados, manipulação de eventos e interfaces gráficas.

---

## 1. 🕹️ Jogo da Forca (HTML5 + JavaScript)

### 📌 Descrição

Um jogo da forca feito com HTML5 e Canvas onde o usuário tenta adivinhar o nome de países. A cada erro, partes do corpo do personagem são desenhadas. O jogo termina quando o usuário acerta todas as letras ou comete 6 erros.

### 📂 Estrutura

- **Canvas** desenha o poste, boneco e tracinhos das letras
- Detecta teclas pressionadas e compara com a palavra
- Controla tentativas, acertos e erros

### 🚀 Como Rodar

1. Crie um arquivo `index.html` com este conteúdo:

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <title>Jogo da Forca</title>
  </head>
  <body>
    <canvas id="paises" width="600" height="400"></canvas>
    <script src="forca.js"></script>
  </body>
</html>
