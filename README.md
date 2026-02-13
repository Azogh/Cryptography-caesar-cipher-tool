# 🔐 Classic Cryptography Lab: Caesar Cipher

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-JS-f7df1e.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Security Focused](https://img.shields.io/badge/Focus-Cybersecurity-red)](#)

---

## 📖 Sobre o Projeto / About

O **Classic Cryptography Lab** é uma ferramenta interativa para cifragem e decifragem de mensagens utilizando o algoritmo de substituição mais antigo da história: a **Cifra de César**. 

Este projeto foi desenvolvido para explorar os fundamentos da lógica de programação e os conceitos iniciais de criptografia simétrica, demonstrando como a manipulação de strings e arrays pode ser aplicada na proteção (ou ofuscação) de dados.

> *An interactive tool to explore the Caesar Cipher, one of the earliest known encryption techniques. Developed to demonstrate string manipulation logic and fundamental cryptographic concepts.*

---

## ✨ Funcionalidades / Features

* **🔒 Cifragem Robusta:** Transformação de texto puro em texto cifrado com base no deslocamento (*shift*).
* **🔓 Decifragem Reversa:** Processo inverso para recuperação da mensagem original.
* **🔢 Deslocamento Customizável:** Permite configurar o número de posições (Key) no alfabeto.
* **📱 Interface Responsiva:** Design limpo e adaptável para diferentes tamanhos de tela.
* **🛡️ Sanitização de Dados:** Tratamento de caracteres especiais e validação de entradas.

---

## 🛠️ Tecnologias / Tech Stack

* **HTML5:** Estrutura semântica.
* **CSS3:** Estilização moderna e layout responsivo.
* **JavaScript (ES6+):** Lógica principal de criptografia e manipulação de DOM.

---

## 🚀 Como Utilizar / Usage

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Azogh/Classic-Cryptography-Lab.git](https://github.com/Azogh/Classic-Cryptography-Lab.git)

---

## 💡 Conceito Técnico

A Cifra de César funciona substituindo cada letra do texto original por uma letra que se encontra um número fixo de posições à frente no alfabeto. Matematicamente, para um deslocamento $n$, a função de cifragem é definida como:

$$E_n(x) = (x + n) \mod 26$$

Onde:
* **x**: É a posição da letra no alfabeto (0 a 25).
* **n**: É o número de posições de deslocamento (chave).
* **mod 26**: Garante que o resultado "gire" dentro do alfabeto de 26 letras.

Este laboratório simula exatamente esse comportamento de forma visual e intuitiva, permitindo o estudo prático da manipulação de caracteres.

---

## 👨‍💻 Autor

**Andre Gustavo Ozga**
*Estudante de Sistemas de Informação | Cybersecurity Enthusiast*
