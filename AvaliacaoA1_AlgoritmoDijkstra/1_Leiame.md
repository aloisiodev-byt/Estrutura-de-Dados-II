# O Algoritmo de Dijkstra tem Árvore Binária?

Entenda a relação entre grafos, filas de prioridade e árvores na busca pelo caminho mínimo.

> Resumo direto: O [Algoritmo de Dijkstra](<https://pt.wikipedia.org/wiki/Algoritmo_de_Dijkstra?utm_source=chatgpt.com>) não é uma árvore binária por si só, mas utiliza uma árvore binária nos bastidores (chamada de Heap Binária) para acelerar a busca pelo menor caminho.

## Como as estruturas se relacionam?

- O Algoritmo (Grafos): Concebido por Edsger Dijkstra, este método resolve o problema do caminho mais curto em grafos com arestas de pesos não negativos, partindo de um vértice de origem até os demais.

- A Fila de Prioridade (Heap Binária): Para decidir rapidamente qual é o próximo vértice não visitado com a menor distância acumulada, o algoritmo costuma usar uma Heap Binária (Min-Heap). Essa estrutura é, na prática, uma árvore binária completa que mantém o menor elemento sempre no topo.

- A Árvore de Caminhos Mínimos: Ao finalizar a execução, o resultado formado pelas rotas ótimas a partir da origem é uma árvore de caminhos mínimos. Porém, ela não precisa ser binária, podendo ter quantos ramos forem necessários de acordo com as conexões do grafo.

## Saiba mais e aprofunde seus estudos

Confira materiais detalhados sobre o funcionamento e a implementação do algoritmo:

- [Artigo completo na Wikipédia](<https://pt.wikipedia.org/wiki/Algoritmo_de_Dijkstra?utm_source=chatgpt.com>) — História, pseudocódigo e análise de complexidade computacional.

- [Introdução detalhada e visual (freeCodeCamp)](<https://www.freecodecamp.org/portuguese/news/algoritmo-de-caminho-de-custo-minimo-de-dijkstra-uma-introducao-detalhada-e-visual/?utm_source=chatgpt.com>) — Passo a passo ilustrado de como os nós são visitados e atualizados.

- [Notas de aula do IME-USP](<https://www.ime.usp.br/~pf/algoritmos_para_grafos/aulas/dijkstra.html?utm_source=chatgpt.com>) — Comparação técnica entre a implementação simples e a otimizada com fila de prioridade (Heap).

Professora Kadidja Valéria Estrutura de Dados II | Estudo dirigido para Avaliação A1 | UDF.
