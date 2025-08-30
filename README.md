# Checkpoint_C
# Comparação de Algoritmos de Ordenação em C

Este projeto implementa e compara o desempenho de três algoritmos de ordenação em C:

- *Bubble Sort*
- *Insertion Sort*
- *qsort* (função da biblioteca padrão C)

O objetivo do projeto é medir o tempo de execução e o número de comparações de cada algoritmo em diferentes cenários e tamanhos de entrada, com o intuito de analisar e comparar a eficiência dos algoritmos.

## Descrição do Projeto

O projeto realiza a ordenação de vetores utilizando três algoritmos distintos e avalia o desempenho em diferentes cenários:

- Vetor aleatório
- Vetor já ordenado (crescente)
- Vetor ordenado reverso
- Vetor quase ordenado (10% fora de ordem)

### Cenários e Tamanhos de Entrada

Os experimentos são realizados com os seguintes tamanhos de vetores:

- 1000 elementos
- 5000 elementos
- 10000 elementos

Cada configuração é executada 5 vezes, e as métricas de desempenho (tempo de execução e número de comparações) são registradas para análise posterior.

## Como Compilar e Executar

### Compilação

Para compilar o programa, utilize o seguinte comando:

```bash
gcc ordenacao.c -o ordenacao
