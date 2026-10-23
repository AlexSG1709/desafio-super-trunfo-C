# 🃏 Jogo Super Trunfo em C

![Linguagem C](https://shields.io)
![Ambiente](https://shields.io)
![Status](https://shields.io)

## 📝 Descrição do Projeto
Este repositório reúne o desenvolvimento completo do jogo **Super Trunfo**, programado inteiramente na **Linguagem C** para execução em console. O projeto demonstra a evolução prática de uma aplicação de terminal, englobando desde a estruturação inicial dos dados e cadastros até o motor lógico de comparação de atributos das cartas.

O projeto está dividido em duas partes fundamentais localizadas na raiz deste repositório:

---

## ⚙️ Módulos do Sistema

### 📁 1. Cadastro de Cartas (`cadastro_cartas.c`)
* **Estrutura de Dados:** Aplicação de variáveis adequadas para modelar as propriedades de cada carta (como código da carta, nome da cidade, população, área em km², PIB e número de pontos turísticos).
* **Entrada de Dados Interativa:** Implementação da leitura formatada de dados via console utilizando funções de captura.
* **Exibição Formatada:** Impressão clara dos dados cadastrados na tela, organizando as informações para conferência do usuário.

### 📁 2. Motor de Lógica do Jogo (`jogo_super_trunfo.c`)
* **Operadores Condicionais:** Desenvolvimento de regras estruturadas (utilizando `if`, `else if` e `else`) para comparar os atributos das cartas em jogo.
* **Cálculo de Propriedades:** Implementação de cálculos aritméticos em tempo de execução para avaliar fatores de desempate e poder das cartas.
* **Determinação de Vencedor:** Lógica automatizada para comparar os dados e imprimir no terminal qual carta foi a vencedora da rodada com base no atributo escolhido.

---

## 🚀 Como Executar os Módulos

Certifique-se de possuir um compilador C (como o `gcc`) configurado no seu sistema.

1. Clone o repositório:
```bash
git clone https://github.com
```

2. Acesse a pasta do projeto:
```bash
cd desafio-super-trunfo-C
```

3. Para testar o **módulo de cadastro**:
```bash
gcc cadastro_cartas.c -o cadastro && ./cadastro
```

4. Para rodar o **jogo com a lógica de comparação**:
```bash
gcc jogo_super_trunfo.c -o jogo && ./jogo
```

---
*Projeto desenvolvido como atividade acadêmica para a plataforma MateCheck.*
