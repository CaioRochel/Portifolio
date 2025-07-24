# Projeto de Análise de Vendas - Loja Fictícia

## Objetivo
Este projeto simula a atuação de um analista de dados em uma empresa varejista. A proposta é analisar um conjunto de vendas para gerar insights sobre desempenho de produtos, regiões e clientes, com foco no aumento da lucratividade.

## Dados
O conjunto de dados contém 500 registros de vendas fictícias com as seguintes colunas:
- ID do Pedido
- Data
- Cliente
- Região
- Categoria
- Produto
- Quantidade
- Preço Unitário
- Receita
- Lucro

## Ferramentas Utilizadas
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook

## Principais Análises Realizadas
- Produtos mais vendidos
- Produtos mais lucrativos
- Vendas por mês
- Lucro por região
- Comparação entre categorias

## Principais Insights
- A categoria "Tecnologia" apresenta a maior receita, mas nem sempre o maior lucro.
- Alguns produtos têm alto volume de vendas com baixa margem — ponto de atenção.
- A região Sudeste concentra grande parte das vendas lucrativas.
- Existe sazonalidade nas vendas em certos meses do ano.

## Visualizações
![categoria](https://github.com/user-attachments/assets/b1a49a3c-f8ec-4dcd-95f6-f755e07cce35)
![maisvendidos](https://github.com/user-attachments/assets/92e0e6e4-00e1-4205-b7f5-081ae9e877ea)
![maislucrativos](https://github.com/user-attachments/assets/1e781121-109d-47ce-8e9d-322a09c3066e)
![receitames](https://github.com/user-attachments/assets/9eef9a2a-7942-4aa0-a187-a5b721dd3b44)
![lucroregiao](https://github.com/user-attachments/assets/8606cdf5-32f2-49c2-ba56-b92dcb1be58c)
## Conclusão
Com base nos dados analisados, recomenda-se:
- Focar em produtos de alta margem, mesmo que vendam menos.
- Investir em marketing nas regiões com bom retorno por venda.
- Analisar sazonalidade para campanhas promocionais em datas-chave.

## Como Executar
1. Clone este repositório
2. Instale os pacotes necessários (`pip install pandas matplotlib seaborn`)
3. Execute o notebook Jupyter `analise_vendas.ipynb`
