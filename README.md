# Cenário 1 x Pseudocódigo de Floyd-Warshall

## O Problema: Vértice Central
O objetivo é identificar o vértice (estação) que possui o menor custo total para alcançar todos os outros vértices da rede. O critério principal para essa escolha é o menor somatório das distâncias do vértice em questão para todos os demais.

## Algoritmo Utilizado: Floyd-Warshall
Para resolver este problema, foi escolhido o algoritmo de Floyd-Warshall.

## Justificativa da Escolha
O algoritmo de Floyd-Warshall é ideal para este cenário porque ele calcula a distância mínima entre todos os pares de vértices do grafo em uma única execução. Como precisamos analisar o somatório das distâncias de cada vértice para todos os outros, ter a matriz completa de distâncias mínimas torna o cálculo da estação central simples e direto.

## A alternativa seria executar o algoritmo de Dijkstra a partir de cada um dos vértices do grafo, o que seria computacionalmente mais complexo para este problema específico.

## Comparativo: Pseudocódigo vs. Implementação em Python
A implementação em Python é uma tradução fiel da lógica do pseudocódigo clássico, adaptada para uma estrutura orientada a objetos.
<img width="704" height="187" alt="image" src="https://github.com/user-attachments/assets/631dd073-0b0f-4a21-834d-b589d47cca18" />

## A implementação em Python : 
<img width="685" height="276" alt="image" src="https://github.com/user-attachments/assets/e4ca68df-fe68-4d23-8bb5-2aa50f18feab" />

## Comparativo Geral : 
<img width="657" height="638" alt="image" src="https://github.com/user-attachments/assets/df5b8b2a-7165-4d44-91ac-833430175ffd" />
