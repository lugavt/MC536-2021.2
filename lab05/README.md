# Aluno
* `240231`: `Lucca Gazotto Vettori`

## Tarefa de Cypher sobre Marcadores e Taxonomia

## Tarefa 1

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, sem considerar as categorias subordinadas.

### Resolução
~~~cypher
MATCH(m:Marcador) MATCH(c:Categoria {id:"Serviços"}) WHERE (m)-[:Pertence]->(c) RETURN m
~~~

## Tarefa 2

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, considerando as categorias subordinadas.

### Resolução
~~~cypher
(escreva aqui a resolução em Cypher)
~~~
