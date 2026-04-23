📈 Análise Semestral: Mercado de Combustíveis no Brasil (2024)
Inteligência de Dados e Monitoramento de Preços com Power BI

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)

🔘 Visão Geral
Este projeto apresenta uma análise técnica e semestral sobre o comportamento dos preços de combustíveis em todo o território brasileiro durante o ano de 2024. O objetivo central foi identificar flutuações de mercado, médias por bandeira e variações regionais, oferecendo suporte para a compreensão da dinâmica de preços na revenda.

O desenvolvimento foi realizado com base nos conhecimentos do curso "Power BI: analisando dados de forma inteligente" da Alura, com foco em transformação de dados e visualização analítica.

🏗️ Estrutura do Modelo (Data Modeling)
A base do sucesso deste dashboard reside na sua arquitetura de dados. Em vez de utilizar uma única tabela "achatada", apliquei o conceito de Star Schema (Esquema Estrela), garantindo escalabilidade e performance:

Tabela Fato (fPrecos): Contém os registros históricos de preços, volumes e métricas de transação.

Tabelas Dimensão: * dBandeiras: Segmentação por distribuidora e marca.

dEstados: Localização geográfica das amostras.

dProdutos: Categorização dos tipos de combustível (Diesel, Etanol, Gasolina, GNV).

dRevenda: Detalhamento dos pontos de venda.

Organização de Medidas: Todas as fórmulas DAX foram centralizadas em uma pasta específica para facilitar a manutenção e leitura do projeto.

Detalhamento das tabelas de dimensões, medidas organizadas e relacionamentos do projeto.

⚙️ Processo de Desenvolvimento (ETL)
O tratamento dos dados foi realizado inteiramente via Power Query, focando em:

Conexão & Extração: Ingestão de dados do portal dados.gov.br.

Limpeza (Cleaning): Padronização de nomes de estados, bandeiras e correção de tipos numéricos.

Enriquecimento: Criação de colunas para facilitar filtros temporais e métricas de comparação percentual.

📉 Insights Analíticos do Semestre
Amplitude de Preços: Identificação de uma diferença percentual de até 51% entre preços mínimos e máximos em determinados estados.

Amostragem: Processamento robusto de 421 mil amostras, garantindo significância estatística para a média geral.

Comportamento Temporal: Visualização clara da tendência de preços ao longo dos meses, destacando períodos de estabilidade e picos de alta.

🖼️ Visualização do Dashboard
Interface final com filtros dinâmicos, KPIs de média e análise de tendência por dia e mês.

📂 Estrutura do Repositório
dashboard/: Arquivo .pbix original.

data/: Documentação sobre a fonte dos dados (dados.gov.br).

imagens/: Screenshots das visões de modelo e relatórios.

## 👤 Autor
**Lucas Oliveira** - *Analista de Dados* [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)]( https://www.linkedin.com/in/lucas-santos-social/)
