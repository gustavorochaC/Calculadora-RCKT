# 🧮 Calculadora React — v2

<img width="1108" height="729" alt="FOTO" src="https://github.com/user-attachments/assets/4ee60a57-3909-45fe-90a4-d8ae68704724" />

Calculadora em React com Tailwind (via CDN). Nesta versão v2, a interface continua igual ao layout anterior, mas agora a calculadora executa operações básicas e tem suporte ao teclado.

## 🌐 Demo
🔗 **[Ver Projeto Online](https://gustavorochac.github.io/Calculadora-Visual/)**

## 🆕 Novidades da v2
- Lógica de cálculo implementada (+, -, X, ÷)
- Vírgula decimal suportada (internamente convertida para ponto)
- Prevenção/substituição de operadores duplicados
- Botões CE (apaga último) e C (limpa tudo)
- Suporte ao teclado: números, + - * / , . Enter (=), Backspace (CE), Esc (C)
- Exibição da operação e do resultado com normalização (X → *, ÷ → /)

## ✨ Funcionalidades
- Tema escuro com gradientes e sombras
- Layout responsivo
- Grid de botões conforme o design
- Histórico visual ao lado (estático nesta versão)

## 🛠️ Tecnologias
- React 18 (UMD)
- Tailwind CSS v4 (browser CDN)
- Babel Standalone (JSX no navegador)
- Google Fonts (Rubik)

## 🚀 Como usar
```bash
# Clone o repositório
git clone https://github.com/gustavorochac/Calculadora-Visual.git

# Abra o arquivo index.html no navegador
```

Observações:
- Esta é uma calculadora didática. O histórico mostrado é estático.
- A vírgula de entrada é convertida para ponto para cálculo e exibida novamente como vírgula no resultado.


