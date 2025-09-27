# Cenario1

# Cenário 1: Encontrando a Estação Central
Este projeto implementa uma solução em Python para o "Cenário 1", que consiste em determinar a estação de metrô mais central em uma rede não-direcionada e ponderada.
# O Problema: Vértice Central
O objetivo é identificar o vértice (estação) que possui o menor custo total para alcançar todos os outros vértices da rede. O critério principal para essa escolha é o menor somatório das distâncias do vértice em questão para todos os demais.
# Algoritmo Utilizado: Floyd-Warshall
Para resolver este problema, foi escolhido o algoritmo de Floyd-Warshall.
# Justificativa da Escolha
O algoritmo de Floyd-Warshall é ideal para este cenário porque ele calcula a distância mínima entre todos os pares de vértices do grafo em uma única execução. Como precisamos analisar o somatório das distâncias de cada vértice para todos os outros, ter a matriz completa de distâncias mínimas torna o cálculo da estação central simples e direto.
A alternativa seria executar o algoritmo de Dijkstra a partir de cada um dos vértices do grafo, o que seria computacionalmente mais complexo para este problema específico.
# Comparativo: Pseudocódigo vs. Implementação em Python
A implementação em Python é uma tradução fiel da lógica do pseudocódigo clássico, adaptada para uma estrutura orientada a objetos.
# Lógica Principal
A essência do algoritmo é um conjunto de três laços aninhados que verificam sistematicamente se um caminho através de um vértice intermediário k é mais curto do que o caminho conhecido até o momento.
# Pseudocódigo Clássico:	

