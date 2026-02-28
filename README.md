# 🃏 Jogo Super Trunfo - Países (Em C)

Bem-vindo ao repositório do **Super Trunfo de Países**! Este é um projeto desenvolvido em linguagem C que simula o clássico jogo de cartas, onde você cadastra dados de cidades e o sistema define automaticamente a carta vencedora com base em seus atributos.

## 📋 Sobre o Projeto

O programa permite o cadastro de duas cartas de cidades, recebendo dados como população, área, PIB e pontos turísticos. A partir desses dados base, o sistema calcula dois atributos adicionais:
* **Densidade Populacional:** Habitantes por km² (neste jogo, quanto *menor*, melhor!).
* **PIB per Capita:** Riqueza dividida pela população.
* **Super Poder:** A soma de todos os atributos (com a densidade populacional invertida), criando um status final de poder da carta.

No final, o programa exibe um relatório detalhado e compara as duas cartas, definindo a vencedora em cada categoria.

## ✨ Funcionalidades

- [x] Leitura segura de dados de diferentes tipos (char, strings, float, unsigned long int).
- [x] Tratamento de buffer de teclado durante as leituras com `scanf`.
- [x] Cálculos matemáticos precisos com conversão de tipos (casting).
- [x] Comparação lógica utilizando operadores relacionais e operador ternário.
- [x] Interface via terminal simples e intuitiva.

## 🚀 Como Executar o Jogo

### Pré-requisitos
Para rodar este código, você precisará de um compilador da linguagem C instalado no seu computador, como o **GCC**.

### Passos para compilar e rodar:

1. Clone este repositório ou baixe o arquivo fonte (`main.c`).
2. Abra o terminal (ou prompt de comando) e navegue até a pasta onde o arquivo está salvo.
3. Compile o código digitando o seguinte comando:
   ```bash
   gcc main.c -o super_trunfo
