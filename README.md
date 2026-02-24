# sql_plano_di-rio_estudo
Vou montar um plano de 8 semanas, com foco em SQL pesado, prática diária e construção de maturidade técnica. A ideia é estudar de segunda a sexta, 1h30 a 2h por dia
📅 Estrutura diária padrão

Todo dia você vai dividir assim:

30 min teoria

60 min prática pesada

15 min revisão + anotações técnicas (GitHub depois)

🔵 SEMANAS 1–2: Fundamentos sólidos (base forte)
🎯 Objetivo:

Dominar SELECT, JOIN, agregações e subqueries sem pensar muito.

✅ Dia 1 – SELECT e filtros

Teoria

SELECT

WHERE

AND / OR

ORDER BY

LIMIT

Exercícios

Buscar clientes de um estado específico

Filtrar pedidos acima de determinado valor

Ordenar por data decrescente

Buscar top 10 maiores pedidos

✅ Dia 2 – Funções de agregação

Teoria

COUNT

SUM

AVG

MIN / MAX

GROUP BY

HAVING

Exercícios

Faturamento por mês

Ticket médio por cliente

Produtos mais vendidos

Estados com faturamento acima de X

✅ Dia 3 – JOIN pesado

Teoria

INNER JOIN

LEFT JOIN

Diferença prática entre eles

Exercícios

Juntar pedidos com clientes

Listar clientes sem pedidos

Total vendido por categoria

Receita por cidade

✅ Dia 4 – Subqueries

Teoria

Subquery no WHERE

Subquery no SELECT

Subquery correlacionada

Exercícios

Clientes que gastaram acima da média

Produto mais caro por categoria

Pedidos acima do faturamento médio mensal

✅ Dia 5 – Desafio da semana

Monte uma query que:

Calcule receita mensal

Compare com mês anterior

Mostre variação percentual

Sem copiar. Pensar como engenheiro.

🔵 SEMANAS 3–4: SQL avançado

Agora começa o nível que diferencia você.

✅ Dia 1 – CTE (WITH)

Refatorar subqueries usando CTE

Criar queries encadeadas

Exercício:
Criar CTE para:

Receita mensal

Receita acumulada

Ranking mensal

✅ Dia 2 – Window Functions (parte 1)

ROW_NUMBER()

RANK()

DENSE_RANK()

Exercícios:

Ranking de clientes por faturamento

Top 3 produtos por categoria

Identificar primeiro pedido do cliente

✅ Dia 3 – Window Functions (parte 2)

SUM() OVER

AVG() OVER

LAG()

LEAD()

Exercícios:

Receita acumulada por mês

Comparar faturamento mês atual vs anterior

Identificar crescimento percentual

✅ Dia 4 – CASE WHEN + lógica avançada

Exercícios:

Classificar clientes (Bronze, Prata, Ouro)

Criar coluna de faixa de preço

Criar flag de cliente recorrente

✅ Dia 5 – Desafio técnico

Criar relatório completo:

Receita mensal

Receita acumulada

Ranking de clientes

Crescimento percentual

Tudo numa única query estruturada.

🔵 SEMANAS 5–6: Performance e modelagem

Aqui você começa a virar engenheiro.

✅ Dia 1 – Índices

Criar índice

Rodar EXPLAIN ANALYZE

Comparar tempo

Exercício:
Criar tabela com 1M registros (gerar via script)
Testar consulta com e sem índice.

✅ Dia 2 – Execution Plan

Entender Seq Scan

Index Scan

Nested Loop

✅ Dia 3 – Modelagem dimensional

Estudar:

Fato

Dimensão

Star Schema

Desenhar um mini Data Warehouse.

✅ Dia 4 – Criar DW na prática

Criar:

dim_cliente

dim_produto

fato_vendas

Inserir dados e consultar.

✅ Dia 5 – Desafio

Criar dashboard SQL-only:

Receita por mês

Receita por categoria

Top clientes

Ticket médio

🔵 SEMANAS 7–8: Mentalidade de Data Engineer
✅ Dia 1 – Carga incremental

Simular:

Tabela staging

Inserir apenas novos registros

✅ Dia 2 – Tratamento de histórico (SCD Type 2)

Simular mudança de estado de cliente mantendo histórico.

✅ Dia 3 – Organização de projeto

Estruturar:

/sql
  /raw
  /staging
  /mart
✅ Dia 4 – Projeto final

Criar pipeline SQL completo:
raw → staging → mart

✅ Dia 5 – Simulado de entrevista

Resolver 10 queries complexas cronometradas.

📌 Regra de ouro

Todo exercício:

Sempre usar CTE quando fizer sentido

Sempre pensar em performance

Sempre escrever query legível

Sempre comentar lógica
