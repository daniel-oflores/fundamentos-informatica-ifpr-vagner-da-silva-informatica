    # Meus Projetos de Fundamentos de Informática - IFPR

Este repositório contém os códigos desenvolvidos durante as aulas práticas da disciplina de Fundamentos de Informática com o Prof. Vagner Simões Santos, utilizando o simulador Simbler.

---

## B4.P1.A3 - Desafios U.L.A.

Nesta atividade, foram desenvolvidos três programas para explorar diferentes aspectos da linguagem Assembly (ASM).

### 1. Desafio da Calculadora (`desafio1_calc.sbl`)

*   **Objetivo:** Calcular a expressão matemática `(100 + 50 - 30) * 2 / 10`.
*   **Comandos Utilizados:** `LOAD`, `ADD`, `SUB`, `STORE`, `MUL`, `DIV`, `HLT`.
*   **Resultado Esperado:** Ao final da execução, o valor **24** é armazenado nos registradores AX e CX.

### 2. Desafio do Porteiro Digital (`desafio2_porteiro.sbl`)

*   **Objetivo:** Simular uma verificação condicional. O programa verifica se o valor inicial (carregado usando `LOAD` é igual a 18.
*   **Comandos Utilizados:** `LOAD`, `CMP` e `JZ`
*   **Lógica de Funcionamento:**
    *   Se o valor de entrada for `18`, o programa termina com `1` em AX.
    *   Se o valor for diferente de `18`, ele termina com `0` em AX.
*   **Conceito-Chave:** Este programa demonstra o uso do **Zero Flag (Z)** para controlar o fluxo de execução com um salto que depende do valor de `Z`

### 3. Desafio da Contagem Regressiva (`desafio3_contagem.sbl`)

*   **Objetivo:** loop simples que decrementa um contador de 5 até 0.
*   **Comandos Utilizados:** `LOAD`, `DEC`, `CMP`, `JZ` e `JMP` .
*   **Lógica de Funcionamento:** O programa entra em um ciclo onde subtrai 1 do valor em AX e verifica se já chegou a zero. Enquanto não for zero, ele volta ao início do loop usando `JMP`. Quando chega a zero, ele usa `JZ` para sair do loop e encerrar.
*   **Conceito-Chave:** Demonstração de uma estrutura de repetição (loop) em Assembly.
