# Para aqueles que desejam ir mais a fundo na pesquisa, e saber mais sobre assuntos técnicos e como o artigo poderia ser aplicado, criamos esse repositório para mostrar como poderia ser feito no SQL. 

# Artigo-CTE
Análise de Clientes Fiéis com Common Table Expressions (CTEs) no SQL
Este projeto tem como objetivo demonstrar como utilizar Common Table Expressions (CTEs) no SQL para identificar e analisar clientes fiéis. A fidelidade do cliente é crucial para qualquer empresa, pois clientes recorrentes tendem a gerar mais receita ao longo do tempo. Este README apresentará quatro exemplos de códigos SQL, cada um com explicações claras para facilitar o entendimento tanto para iniciantes quanto para especialistas na área.

Exemplo 1: Definir Métricas de Fidelidade
Neste exemplo, usamos uma CTE para calcular o total de compras e a média de gasto por cliente. A CTE é como uma consulta temporária que pode ser referenciada dentro de outra consulta SQL. Primeiro, agrupamos as compras por ClienteID e calculamos o número total de compras (TotalCompras) e o gasto médio (MediaGasto).

![Compras](https://github.com/user-attachments/assets/56c4e93b-4036-468d-a476-deaa8964035f)


Exemplo 2: Filtrar Clientes Fiéis
Aqui, filtramos os clientes que atendem a critérios específicos de fidelidade, como fazer pelo menos 5 compras e ter um gasto médio acima de 50. Adicionamos outra CTE para selecionar apenas esses clientes.

![Filtro](https://github.com/user-attachments/assets/ab6b8b05-3416-4d81-96c8-c6242a9d600a)


Exemplo 3: Geração de Relatórios
Neste exemplo, criamos um índice de lealdade multiplicando o total de compras pelo gasto médio. Isso nos ajuda a priorizar os clientes com base em seu valor para a empresa.

![Relatório](https://github.com/user-attachments/assets/73f48124-e6e2-43b0-bffd-6ec546f89baf)


Exemplo 4: Atualizar Critérios de Fidelidade
Finalmente, mostramos como ajustar os critérios de fidelidade para refletir novas metas de negócio, como aumentar o número mínimo de compras para 10 e o gasto médio para 100.

![Atulização critérios](https://github.com/user-attachments/assets/0dd63ecb-898e-4be0-ac51-e37603e3e500)

