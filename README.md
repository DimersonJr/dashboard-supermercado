# 📊 Dashboard de Vendas de Supermercado

Este projeto apresenta uma análise completa do desempenho de um supermercado, utilizando dados de vendas, clientes e produtos para gerar insights estratégicos através de um dashboard interativo.
---

## 🎯 Perguntas de Negócio Respondidas

O dashboard foi desenvolvido para responder às seguintes perguntas:

### Página 1 — Visão Geral
- Como está a **receita total do supermercado**?
- Qual o **ticket médio por compra**?
- Como evoluem as **vendas ao longo do tempo**?
- Quais são os **países com maior número de clientes**?
- Existe uma **tendência de crescimento nas vendas**?

### Página 2 — Produtos e Categorias
- Quais produtos geram mais **receita**?
- Quais produtos têm maior **volume de vendas**?
- Qual é o **produto mais vendido**?
- Qual é o **produto mais rentável**?
- Qual categoria é **líder em receita**?
- Quais categorias vendem muito, mas geram menos valor?
- Como os pedidos estão distribuídos entre os países?
---

## 🎨 Justificativa do Design

O design do dashboard foi pensado para ser **simples, intuitivo e focado na tomada de decisão**.

- Utilização de **cores escuras** para melhor contraste e leitura
- Destaque para os **KPIs principais no topo**, facilitando visão rápida
- Organização em duas páginas, separando a visão executiva da visão analítica:
  - **Página 1:** visão geral do negócio
  - **Página 2:** análise detalhada de produtos, categorias e distribuição de pedidos
- Uso de gráficos adequados para cada tipo de análise:
  - Linha e colunas → tendência e comparação ao longo do tempo
  - Barras → comparação entre produtos, categorias e países
  - Rosca → distribuição percentual dos pedidos por país
  - Gauge → indicador de desempenho do ticket médio

---

## KPIs Criados

### Receita Total
Total gerado pelas vendas no período analisado.

### Pedidos
Quantidade total de pedidos realizados.

### Ticket Médio
Valor médio por pedido.

### Produtos Vendidos

Total de itens vendidos no período.

### Clientes Ativos

Número de clientes únicos que realizaram compras.

### Produto Mais Vendido

Produto com maior volume de vendas.

### Produto Mais Rentável

Produto com maior geração de valor.

### Categoria Líder em Receita

Categoria com maior participação no faturamento total.

### Pedidos por País

Análise da distribuição de pedidos entre os países atendidos.

```DAX
Ticket Medio = DIVIDE([Receita], [Pedidos])


## 💡 Considerações Finais
O dashboard permite uma visão clara da saúde do negócio, destacando padrões de crescimento, comportamento de clientes e desempenho de produtos, auxiliando na tomada de decisões estratégicas.