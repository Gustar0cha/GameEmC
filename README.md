
# Jogo de Operações Matemáticas

Este é um jogo simples de operações matemáticas em C, onde o jogador deve resolver equações de adição, subtração ou multiplicação. O jogo possui diferentes níveis de dificuldade, que aumentam os valores dos números nas operações.

## Funcionalidades

- **Níveis de dificuldade:** O jogador pode escolher entre 5 níveis de dificuldade, que determinam a faixa de valores utilizados nas operações:
  - **1:** Fácil (0 a 10)
  - **2:** Médio (0 a 100)
  - **3:** Difícil (0 a 1000)
  - **4:** Insano (0 a 10000)
  
- **Operações:** O jogo suporta três operações:
  - **Adição**
  - **Subtração**
  - **Multiplicação**

- **Pontuação:** O jogador ganha pontos ao acertar as respostas das operações.

- **Reinício:** Ao final de cada rodada, o jogador pode optar por continuar jogando ou finalizar o jogo.

## Como jogar

1. **Compilação:**
   Compile o código usando um compilador C. Exemplo:
   ```bash
   gcc nome_do_arquivo.c -o jogo
   ```

2. **Execução:**
   Execute o jogo no terminal:
   ```bash
   ./jogo
   ```

3. **Escolha do nível de dificuldade:**
   O jogador será solicitado a escolher um nível de dificuldade entre 1 e 5.

4. **Resolução das operações:**
   O jogo apresentará uma operação matemática para ser resolvida, e o jogador deve inserir a resposta.

5. **Continuação do jogo:**
   Após cada resposta, o jogador pode optar por continuar jogando ou finalizar.

## Exemplo de uso

```bash
Informe o nivel de dificuldade desejado [1, 2, 3 ou 4]:
3
Informe o resultado para a seguinte operação: 
450 + 128
578
Resposta correta!
Voce tem 1 ponto(s).
Deseja continuar jogando? [1 - sim, 0 - nao]
```

## Estrutura do código

- **`typedef struct`**: Define a estrutura `Calcular` que armazena os valores e operações matemáticas.
- **Funções**:
  - `jogar()`: Gerencia o fluxo do jogo.
  - `mostrarInfo()`: Exibe informações sobre a operação atual (não utilizada no fluxo principal).
  - `somar()`, `diminuir()`, `multiplicar()`: Executam a operação correspondente e verificam a resposta do jogador.

## Requisitos

- Um compilador C (ex.: GCC).

## Contribuição

Sinta-se à vontade para contribuir com melhorias ou correções. Para contribuir, siga os passos:


## Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
