# Jogo 2048 - Implementação em Python

Este desenvolvimento se baseou no 2° problema apresentado da displina MI-Algoritmos, da UEFS (Universidade Estadual de Feira de Santana), que tinha como intuito a absorção do conteudo básico de algoritmos com ênfase na utilização de funções, afim de compreender lógica e sintaxe de programação por meio da metodologia PBL (Problem Based Learning).

## Sumário

  - [Informações Gerais](#informações-gerais)
    - [Declaração de Autoria](#declaração-de-autoria)
  - [Descrição do Projeto](#descrição-do-projeto)
    - [Funcionalidades Principais](#funcionalidades-principais)
    - [Estrutura do Código](#estrutura-do-código)
  - [Instruções para Jogar](#instruções-para-jogar)
  - [Requisitos](#requisitos)
  - [Controles do Jogo](#controles-do-jogo)
  - [Exemplo de Interface no Console](#exemplo-de-interface-no-console)
  - [Conclusão](#conclusão)

## Informações Gerais

- **Sistema Operacional**: Windows 10
- **Versão Python**: 3.11.5 (64-bit)
- **Autor**: João Marcelo Nascimento Fernandes
- **Componente Curricular**: Algoritmos I
- **Data de Conclusão**: 04/10/2023

### Declaração de Autoria
Declaro que este código foi elaborado por mim de forma individual e não contém nenhum trecho de código de outro colega ou de outro autor, tais como provindos de livros, apostilas, páginas ou documentos eletrônicos da Internet. Qualquer trecho de código de outra autoria que não a minha está destacado com uma citação para o autor e a fonte do código, e estou ciente que estes trechos não serão considerados para fins de avaliação.

## Descrição do Projeto

Este projeto é uma implementação do popular jogo **2048** em Python, que consiste em mover os blocos numerados em uma grade de 4x4 para somá-los. O objetivo do jogo é alcançar a peça de valor **2048**.

### Funcionalidades Principais

- **Movimentação**: O jogador pode mover as peças nas direções **W** (cima), **A** (esquerda), **S** (baixo) e **D** (direita). As peças são somadas quando duas com o mesmo valor colidem.
- **Pontuação**: Cada soma entre peças incrementa a pontuação do jogador.
- **High Score**: O jogo mantém um registro da maior pontuação atingida e do número mínimo de jogadas necessárias para alcançá-la.
- **Detecção de fim de jogo**: O jogo detecta quando o jogador vence (atinge a peça 2048) ou perde (não há mais jogadas possíveis).
- **Reinício de jogo**: Ao fim de uma partida, o jogador pode optar por reiniciar o jogo ou encerrá-lo.

### Estrutura do Código

1. **Funções Principais**:
   - `gerarMatriz()`: Gera a matriz inicial de 4x4 preenchida com zeros.
   - `startGame(matriz)`: Inicia o jogo, colocando duas peças aleatórias (2 ou 4) na matriz.
   - `exibirMatriz(matriz)`: Exibe a matriz no console.
   - `matrizParaComparacao(matriz)`: Cria uma cópia da matriz para comparação antes e após os movimentos.
   - `spawnCasas(matriz)`: Gera um novo valor (2 ou 4) em uma casa vazia após cada jogada.
   - `movimentoSoma(entrada)`: Controla os movimentos (W, A, S, D) e realiza as somas de peças quando necessário.
   - `verifJogadas(matriz)`: Verifica se ainda existem jogadas possíveis.

2. **Programa Principal**:
   - O jogo roda em um loop até que o jogador vença ou perca, permitindo que ele jogue novamente após cada partida.

### Instruções para Jogar

1. Execute o script Python.
2. Use as teclas **W** (cima), **A** (esquerda), **S** (baixo), e **D** (direita) para mover as peças.
3. O jogo termina quando você atinge a peça 2048 ou quando não houver mais jogadas possíveis.
4. Após o fim de uma partida, você pode optar por reiniciar o jogo ou sair.

### Requisitos

- Python 3.11.5 ou superior
- Sistema operacional compatível (o código foi testado no Windows 10)

### Controles do Jogo

| Tecla | Ação          |
|-------|---------------|
| W     | Mover para cima |
| A     | Mover para a esquerda |
| S     | Mover para baixo |
| D     | Mover para a direita |

## Conclusão

Esta implementação simples do jogo **2048** oferece uma experiência completa no console. O código foi organizado de forma clara para facilitar a leitura e a compreensão das operações de movimentação e soma, bem como da lógica do jogo.

**Divirta-se jogando 2048!**

