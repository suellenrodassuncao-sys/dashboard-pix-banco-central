# Dashboard de Transações PIX

Painel em Power BI que analisa as transações PIX de jan. 2025 a jul. 2026, com foco em valores movimentados, quantidade de transações e ticket médio.

## Dados
Dados do Banco Central do Brasil, coletados por API e planilhas do Excel.

## Tratamento (Power Query)
- Remoção de duplicados e de linhas em branco

## Medidas (DAX)
Criei as medidas de todas as análises do painel, como valor total, quantidade de transações e ticket médio.

## O que o painel mostra
- Indicadores de valor total, quantidade de transações e ticket médio
- Comparativo entre pessoa física e jurídica (pagador e recebedor) por mês
- Evolução dos valores pagos e recebidos
- Ranking de municípios por valor transacionado
- Filtros por ano e mês, estado e município

## Principais conclusões
- **Escala:** de jan. 2025 a jul. 2026, as transações somaram R$ 3,86 tri em 10 bi de operações, com ticket médio de R$ 384.
- **Pessoa jurídica paga mais valor:** nos meses de 2025 analisados, o valor pago por pessoas jurídicas foi maior que o das pessoas físicas, como em julho (R$ 147 bi contra R$ 110 bi).
- **Municípios:** Porto Alegre, Belo Horizonte e Manaus lideram o ranking de valor total pago por município.
