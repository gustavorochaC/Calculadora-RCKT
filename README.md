# 🧮 Calculadora React — v2

<img width="1530" height="763" alt="Screenshot_1" src="https://github.com/user-attachments/assets/a94a3575-26b2-41da-bb14-49d3db65cd02" />


Calculadora em React (via UMD) com Tailwind no navegador. Mantém a estética do layout e agora possui histórico dinâmico usando Context API.

## 🌐 Demo
🔗 **[Ver Projeto Online](https://gustavorochac.github.io/Calculadora-RCKT/)**

## 🆕 O que há de novo nesta versão
- Context API para compartilhar o histórico entre componentes
- Histórico dinâmico: cada “=” adiciona `operação=resultado`
- Mensagem “Nenhuma Operação Recente” quando não há histórico
- Botões:
  - C → limpa tudo
  - CE → apaga o último caractere da operação
  - = → calcula a expressão atual
- Entrada com vírgula: converte `,` para `.` para calcular e volta a exibir com `,`
- Continuidade após resultado:
  - Se digitar número, inicia nova operação
  - Se clicar operador, continua a partir do resultado anterior
- Layout responsivo preservado

## ✨ Funcionalidades
- Operações básicas: `+`, `-`, `*`, `/`
- Display com operação (linha superior) e resultado (linha principal)
- Histórico renderizado em lista ao lado (usa Context API)
- Tema escuro com gradientes e sombras
- Google Font Rubik aplicada ao projeto

## 🛠️ Tecnologias
- React 18 (UMD)
- ReactDOM 18 (UMD)
- Babel Standalone (JSX direto no navegador)
- Tailwind CSS v4 (browser CDN)
- Google Fonts (Rubik)

## 🚀 Como usar
```bash
# Clone o repositório
git clone https://github.com/gustavorochac/Calculadora-RCKT.git

# Abra o arquivo index.html no navegador (duplo clique ou:
# Windows)
start index.html
```

## 🧩 Principais componentes
- Calculator: lógica de entrada, cálculo e grid de botões
- CalculatorDisplay: exibe operação e resultado
- OperationHistory: lista o histórico de operações
- CalculatorContext/Provider: mantém o histórico em memória

## ⚠️ Observações
- Projeto com fins didáticos. A avaliação da expressão usa `eval` após normalização; não utilize este método com entradas não confiáveis em produção.
- O histórico é volátil (memória) e se perde ao recarregar a página.


