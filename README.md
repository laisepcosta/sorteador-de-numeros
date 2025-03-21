# 📌 **Projeto: Sorteador de Números**  

![image](https://github.com/user-attachments/assets/e77b9ad6-c656-457d-87d5-cb85b53cef70)

## 📖 **Descrição**  
Este repositório contém um projeto desenvolvido para praticar a manipulação de elementos HTML com JavaScript. O projeto é um sorteador de números onde os usuários podem definir a quantidade de números a serem sorteados e o intervalo de sorteio, com a exibição dos números sorteados na interface.

## 🚀 **Tecnologias Utilizadas**  
- HTML5  
- CSS3  
- JavaScript (DOM Manipulation)

## 🎯 **Conceitos Aplicados**  
- Análise da estrutura HTML para planejamento da funcionalidade  
- Recuperação de elementos com `document.getElementById()`  
- Armazenamento de elementos em variáveis JavaScript  
- Manipulação de classes CSS com `classList.add()`, `classList.remove()` e `classList.contains()`  
- Modificação do texto de elementos com `innerHTML`  
- Geração de números aleatórios com `Math.random()`  
- Uso de condições (`if/else`) para alterar o status dos botões  

## 📂 **Estrutura do Projeto**  
📁 sorteador-de-numeros  
│-- 📄 index.html  
│-- 📄 style.css  
│-- 📄 app.js  
│-- 📁 img  

## ⚙️ **Como Executar**  
1. Clone este repositório:
   ```bash
   git clone https://github.com/laisepcosta/sorteador-de-numeros.git
2. Acesse a pasta do projeto:
     ```bash
    cd sorteador-de-numeros
3. Abra o arquivo index.html em um navegador web.

## 🔄 **Lógica da Funcionalidade**
A página permite que o usuário insira a quantidade de números e o intervalo para o sorteio. O funcionamento da interação é o seguinte:

- O botão **Sortear** chama a função `sortear()`, que:
  - Recupera os valores dos campos de entrada.
  - Gera os números aleatórios dentro do intervalo definido.
  - Exibe os resultados na página.
  - Desabilita o botão **Sortear** e habilita o botão **Reiniciar**.
- O botão **Reiniciar** chama a função `reiniciar()`, que:
  - Limpa os campos de entrada e os resultados.
  - Restaura o estado do botão **Sortear** para ser clicável novamente.

## 📌 **Funcionalidade Implementada**
O projeto permite ao usuário inserir dados para o sorteio e interagir com os botões, alterando dinamicamente o estado da interface conforme os números são sorteados ou reiniciados.

## **🛠 Melhorias Futuras**
- Implementação de animações para a transição dos resultados.
- Adição de validações de entradas (por exemplo, garantir que o intervalo esteja correto).
- Adicionar suporte para salvar o histórico de sorteios.
