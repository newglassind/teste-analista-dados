# Base de Dados Sintética — Teste Analista de Dados

Esta pasta contém uma base fictícia para o teste técnico de Analista de Dados.

Arquivos disponíveis:

- `dados/vendas_pedidos.csv` — itens de pedidos/vendas/faturamento, com 12,045 linhas.
- `dados/devolucoes.csv` — devoluções vinculadas ou não a notas fiscais, com 1,850 linhas.
- `dados/custos_produtos.csv` — custos estimados por produto, com 178 linhas.
- `dados/metas_vendedores.csv` — metas mensais por vendedor, com 148 linhas.

Os arquivos estão em CSV com separador `;` e codificação UTF-8 com BOM.

## Importante

A base foi criada propositalmente com inconsistências semelhantes às encontradas em ambientes reais, como:

- nomes de clientes e vendedores com variações;
- datas em formatos diferentes;
- valores monetários com formatos diferentes;
- campos vazios;
- duplicidades;
- status com grafias diferentes;
- devoluções que podem ocorrer em mês diferente da venda;
- produtos sem custo ou com custo duplicado;
- pedidos cancelados ou em aberto com valores preenchidos;
- bonificações que podem distorcer a visão de faturamento bruto.

O objetivo do teste não é apenas montar um dashboard, mas demonstrar raciocínio, tratamento de dados, definição de premissas e questionamento dos requisitos.
