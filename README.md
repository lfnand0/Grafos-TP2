# Trabalho Prático 2
Determina os caminhos disjuntos em um grafo direcionado

# UTILIZAÇÃO

## -prob [float]: 
### Probabilidade que dois vértices tenham uma aresta em comum 
* (Utilizado na geração de grafos aleatórios)
* Caso não seja utilizado a probabilidade será 0.3
* Exemplo: -prob 0.1

## -arq [string]: 
### Diretório de um arquivo txt com a matriz de adjacência de um grafo
* Exemplo: -arq "./grafos cíclicos/50.txt"

## -ver [int]: 
### Número de vértices a ser usado na geração de grafo
* Caso não seja utilizado o número de vértices será 10
* Exemplo: -ver 100

## -ori [int]: 
### Vértice de origem
* Caso não seja utilizado, o vértice de origem será 0
* Exemplo: -ori 1

## -des [int]: 
### Vértice de destino
* Caso não seja utilizado, o vértice de destino será n - 1
* Exemplo: -des 9

## -cam [string]: 
### Diretório para salvar os caminhos disjuntos encontrados
* Caso não seja utilizado, os caminhos serão salvos em "./disjuntos.txt"
* Exemplo: -cam "./out/caminhos_disjuntos.txt"

## -w [string]: 
### Diretório para salvar o grafo gerado
* Caso não seja utilizado o grafo gerado não será salvo
* Exemplo: -w "./grafos simples/50.txt"

## -ciclo: Gera um grafo cíclico

## -completo: Gera um grafo completo
