# Artigo-CTE
Análise de Clientes Fiéis com Common Table Expressions (CTEs) no SQL
Este projeto tem como objetivo demonstrar como utilizar Common Table Expressions (CTEs) no SQL para identificar e analisar clientes fiéis. A fidelidade do cliente é crucial para qualquer empresa, pois clientes recorrentes tendem a gerar mais receita ao longo do tempo. Este README apresentará quatro exemplos de códigos SQL, cada um com explicações claras para facilitar o entendimento tanto para iniciantes quanto para especialistas na área.

Exemplo 1: Definir Métricas de Fidelidade
Neste exemplo, usamos uma CTE para calcular o total de compras e a média de gasto por cliente. A CTE é como uma consulta temporária que pode ser referenciada dentro de outra consulta SQL. Primeiro, agrupamos as compras por ClienteID e calculamos o número total de compras (TotalCompras) e o gasto médio (MediaGasto).

Exemplo 2: Filtrar Clientes Fiéis
Aqui, filtramos os clientes que atendem a critérios específicos de fidelidade, como fazer pelo menos 5 compras e ter um gasto médio acima de 50. Adicionamos outra CTE para selecionar apenas esses clientes.

Exemplo 3: Geração de Relatórios
Neste exemplo, criamos um índice de lealdade multiplicando o total de compras pelo gasto médio. Isso nos ajuda a priorizar os clientes com base em seu valor para a empresa.

Exemplo 4: Atualizar Critérios de Fidelidade
Finalmente, mostramos como ajustar os critérios de fidelidade para refletir novas metas de negócio, como aumentar o número mínimo de compras para 10 e o gasto médio para 100.
