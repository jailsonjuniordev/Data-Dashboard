# Portfólio de Análise de Dados — AdventureWorks

Projetos de análise de dados em Python feitos a partir da base **AdventureWorks_Sales.xlsx** (vendas de uma loja de bicicletas).

Cada análise fica em uma pasta e responde a uma **pergunta diferente**. Assim fica claro quando usar cada tipo de análise.

**Ferramentas:** Python, Pandas, Matplotlib e Seaborn.

## Análises

| # | Análise | Pergunta que responde | Quando usar | Status |
|---|---------|-----------------------|-------------|--------|
| 1 | **Exploratória** | O que está sendo vendido, onde e em qual canal? | Quando você está conhecendo uma base nova e quer entender o básico antes de aprofundar. | ✅ Pronta |
| 2 | **Clientes perdidos** | Quais fatores estão ligados aos clientes que pararam de comprar? | Quando a empresa quer entender por que perde clientes e onde agir para mantê-los. | ✅ Pronta |
| 3 | **Tendência no tempo** | Como as vendas mudam ao longo do tempo? Existem meses melhores? | Quando é preciso planejar estoque, metas ou campanhas de acordo com a época do ano. | 🔜 Planejada |
| 4 | **Produtos e lucro** | Quais produtos e categorias realmente dão lucro? | Quando é preciso decidir o que promover, priorizar ou deixar de vender. | 🔜 Planejada |
| 5 | **Segmentação de clientes (RFM)** | Que grupos de clientes existem e quais merecem mais atenção? | Quando se quer fazer ações diferentes para cada tipo de cliente (os que compram muito, os que sumiram etc.). | 🔜 Planejada |

## Estrutura do repositório

```
├── README.md
├── AdventureWorks_Sales.xlsx
├── 01_exploratoria/
├── 02_clientes_perdidos/
├── 03_tendencia_no_tempo/
├── 04_produtos_e_lucro/
└── 05_segmentacao_rfm/
```

## Como rodar

1. Baixe o repositório e abra o notebook da análise que quiser no **Jupyter Notebook** ou no **Google Colab**.
2. Mantenha o arquivo `AdventureWorks_Sales.xlsx` na raiz do repositório: os notebooks leem a planilha da pasta acima (`../AdventureWorks_Sales.xlsx`). Se mudar a planilha de lugar, ajuste o caminho na célula de importação.
3. Execute as células em ordem.

## Observação

Esta base não tem uma coluna de cancelamento. Por isso, na análise de clientes perdidos, considerei **perdido** o cliente que não compra há mais de 180 dias (contando até a última data da base).
