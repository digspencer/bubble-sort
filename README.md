# bubble-sort
O Bubble Sort é um algoritmo de classificação (ou ordenação) simples que funciona comparando pares de elementos adjacentes e trocando-os de posição se estiverem na ordem errada. Ele recebe esse nome devido à forma como os elementos "borbulham" para suas posições corretas à medida que a lista é percorrida repetidamente.

O processo básico do Bubble Sort é o seguinte:

1. Começando no início da lista, compare o primeiro elemento com o segundo elemento. Se estiverem fora de ordem, troque-os de posição.
2. Em seguida, compare o segundo elemento com o terceiro elemento e faça a troca, se necessário. Continue comparando e trocando elementos adjacentes até chegar ao final da lista.
3. Agora, repita os passos 1 e 2 para a lista novamente, começando do início.
4. Continue repetindo esses passos até que não sejam necessárias mais trocas durante uma iteração completa da lista.

Esse algoritmo funciona corretamente porque, em cada iteração, o elemento mais pesado (maior) "borbulha" para a posição correta no final da lista. Portanto, após várias iterações, todos os elementos ficam ordenados.

Apesar de sua simplicidade, o Bubble Sort não é muito eficiente para grandes conjuntos de dados, pois requer várias comparações e trocas. Ele tem uma complexidade de tempo médio e pior caso de O(n^2), onde "n" é o número de elementos na lista. Existem outros algoritmos de ordenação mais eficientes, como o Merge Sort e o Quick Sort, que são preferíveis para lidar com grandes quantidades de dados.
