# 📊 Dashboard de Vendas de Supermercado

Este projeto apresenta uma análise completa do desempenho de um supermercado, utilizando dados de vendas, clientes e produtos para gerar insights estratégicos através de um dashboard interativo.
---

## 🎯 Perguntas de Negócio Respondidas

O dashboard foi desenvolvido para responder às seguintes perguntas:

- Como está a **receita total do supermercado**?
- Qual o **ticket médio por compra**?
- Como evoluem as **vendas ao longo do tempo**?
- Quais são os **países com maior número de clientes e pedidos**?
- Quais produtos geram mais **receita**?
- Quais produtos têm maior **volume de vendas**?
- Quais categorias são mais **lucrativas vs mais vendidas**?
- Existe uma **tendência de crescimento nas vendas**?

---

## 🎨 Justificativa do Design

O design do dashboard foi pensado para ser **simples, intuitivo e focado na tomada de decisão**.

- Utilização de **cores escuras** para melhor contraste e leitura
- Destaque para os **KPIs principais no topo**, facilitando visão rápida
- Organização em duas páginas:
  - **Página 1:** visão geral do negócio
  - **Página 2:** análise detalhada de produtos e categorias
- Uso de gráficos adequados para cada tipo de análise:
  - Linha → tendência ao longo do tempo
  - Barras → comparação entre categorias/produtos
  - Rosca → distribuição percentual
  - Gauge → indicador de desempenho

---

## 📌 KPIs Criados

### 💰 Receita Total
Total gerado pelas vendas no período analisado.

---

### 📦 Pedidos
Quantidade total de pedidos realizados.

---

### 🧾 Ticket Médio
Valor médio por pedido.

```DAX
Ticket Medio = DIVIDE([Receita], [Pedidos])

## 💡 Considerações Finais
O dashboard permite uma visão clara da saúde do negócio, destacando padrões de crescimento, comportamento de clientes e desempenho de produtos, auxiliando na tomada de decisões estratégicas.