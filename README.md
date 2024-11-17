# 🎮 Projeto Nim

O projeto **Nim** é uma implementação do clássico jogo de estratégia **Nim**, onde dois jogadores alternam turnos para retirar objetos de pilhas. O objetivo do jogo é evitar ser o jogador que tirar o último objeto. A estratégia do jogo envolve uma análise cuidadosa das pilhas, já que a vitória pode ser garantida com a aplicação de um cálculo matemático simples, conhecido como *Nim-Sum*.

## 🔧 Funcionalidades

- **Jogabilidade**: Dois jogadores podem se alternar, retirando objetos das pilhas até que um vença o jogo.
- **Estratégia de Vitória**: O jogo é baseado na análise de *Nim-Sum*, uma técnica matemática para garantir a vitória.
- **Modo para Dois Jogadores**: Jogadores humanos jogam alternadamente no mesmo dispositivo.
- **Interface Simples**: O jogo possui uma interface simples e intuitiva para facilitar a experiência.

## 🖥️ Tecnologias Utilizadas

- **Python**: A implementação do jogo é feita em Python, utilizando conceitos de estrutura de dados como pilhas.
- **Terminal/Console**: O jogo é executado no terminal/console, com interação através de texto.

## 🎯 Objetivo do Jogo

O jogo envolve um número de pilhas de objetos, e a cada turno, um jogador deve retirar qualquer número de objetos de uma única pilha. O objetivo é evitar ser o jogador que retira o último objeto de todas as pilhas.

### Regras:

1. O jogo começa com algumas pilhas de objetos.
2. Em cada turno, o jogador deve escolher uma pilha e retirar um número qualquer de objetos dessa pilha.
3. O jogo continua até que todos os objetos sejam retirados.
4. O jogador que retirar o último objeto perde o jogo.

## ⚙️ Como Jogar

1. **Inicie o Jogo**: Execute o arquivo `nim.py` para começar o jogo.
2. **Escolha uma Pilha**: Cada jogador pode escolher uma pilha e decidir quantos objetos retirar dessa pilha.
3. **Estratégia**: Aplique a estratégia de *Nim-Sum* para aumentar suas chances de ganhar. O *Nim-Sum* é calculado fazendo uma operação XOR (exclusive OR) de todos os números de objetos em cada pilha.

## 📌 Como Rodar o Projeto

Para jogar, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/larissadcew/nim.git
