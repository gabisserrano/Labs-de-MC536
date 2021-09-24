# Aluno
* 216698: Gabriella Serrano Santana
## Tarefa de Cypher sobre Marcadores e Taxonomia
### Tarefa 1
Escreva em Cypher uma consulta que retorne os marcadores da categoria Serviços, sem considerar as categorias subordinadas.
#### Resolução
MATCH (d1:Marcador)

MATCH (d2:Categoria {id:"Serviços"})

WHERE (d1)-[:Pertence]->(d2)

RETURN d1
### Tarefa 2
Escreva em Cypher uma consulta que retorne os marcadores da categoria Serviços, considerando as categorias subordinadas.
#### Resolução
MATCH (d3:Marcador)

MATCH (d4:Categoria {id:"Serviços"})

MATCH (d5:Categoria)

MATCH (d6:Categoria)

WHERE (d5)-[:Superior]->(d4) AND (d6)-[:Superior]->(d5) AND  (d3)-[:Pertence]->(d4) OR (d3)-[:Pertence]->(d5) OR (d3)-[:Pertence]->(d6)

RETURN d3
