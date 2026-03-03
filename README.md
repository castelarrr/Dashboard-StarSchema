***# 📊 Dashboard de Vendas de Dispositivos Móveis - Star Schema

Este projeto foi desenvolvido como parte de um desafio prático de modelagem de dados na DIO. O objetivo principal foi aplicar os conceitos de Star Schema (Esquema Estrela) em um conjunto de dados fictícios de vendas de dispositivos tecnológicos, como iPhone 15 e Galaxy S23.

🎯 Objetivo do Projeto
Transformar uma tabela única (flat table) em uma estrutura dimensional otimizada para Business Intelligence. A partir dos dados brutos, foram criadas relações entre vendas, produtos, clientes e localizações para facilitar a extração de insights e a performance dos cálculos.

Dados Utilizados:
Produtos: iPhone 15, Galaxy S23, MacBook Air, Mouse Gamer.

Categorias: Celulares, Notebooks, Acessórios.

Cidades: São Paulo, Rio de Janeiro, Curitiba, Belo Horizonte, Porto Alegre e Recife.

Período: Janeiro de 2024.

🏗️ Modelagem Dimensional (Star Schema)
Para garantir a eficiência do modelo, os dados foram estruturados em:

Tabela Fato (fVendas): Contém as métricas de quantidade, preço unitário, custo unitário e as chaves de ligação.

Tabelas Dimensão:

dProdutos: Detalhes de modelos e categorias.

dClientes: Informações de compradores e cidades.

dCalendario: Organização temporal das vendas.

📈 Visualização e Insights
O relatório permite analisar:

Faturamento por Categoria: Desempenho comparativo entre celulares e acessórios.

Performance Regional: Identificação das cidades com maior volume de vendas.

Análise de Margem: Diferença entre preço de venda e custo unitário por produto.

🛠️ Tecnologias Utilizadas
Power BI: Modelagem de dados, Power Query e DAX.

Excel/CSV: Fonte de dados fictícios.

Star Schema: Metodologia de design de banco de dados.
