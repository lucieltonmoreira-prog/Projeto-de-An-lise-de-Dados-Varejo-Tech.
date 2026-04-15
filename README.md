# Projeto-de-Analise-de-Dados-Varejo-Tech.
A empresa precisava entender o impacto das vendas por região e limpar dados inconsistentes

Projeto de Análise de Vendas: De Dados Brutos ao Insight
Este projeto demonstra um pipeline completo de análise de dados (ETL) utilizando Python (Pandas) para o tratamento dos dados e Power BI para a criação de um dashboard estratégico. O objetivo foi transformar uma base de dados de varejo fictícia em informações visuais que auxiliem na tomada de decisão.

Tecnologias Utilizadas
Python 3.12: Processamento e manipulação de dados.

Pandas: Biblioteca principal para limpeza e transformação.

Power BI Desktop: Modelagem e visualização de dados.

Markdown: Documentação do projeto.

O Problema de Negócio
A empresa fictícia apresentava dificuldades em visualizar seu faturamento por região devido a inconsistências na base de dados (valores nulos, registros duplicados e formatos de data incorretos). O objetivo deste projeto foi limpar esses dados e gerar um dashboard que respondesse:

Qual o faturamento total e ticket médio?

Quais cidades possuem o melhor desempenho de vendas?

Qual categoria de produto é o carro-chefe da empresa?

Etapas do Projeto
1. ETL e Limpeza com Pandas
Utilizei os conceitos fundamentais da biblioteca Pandas para garantir a qualidade dos dados:

Tratamento de Nulos: Identificação e preenchimento de preços ausentes utilizando a média (função .fillna()).

Deduplicação: Remoção de registros idênticos para evitar inflação nos números (função .drop_duplicates()).

Engenharia de Atributos: Criação da coluna Faturamento_Total e extração de mês/ano para análises temporais.

2. Visualização no Power BI
Com os dados limpos, exportei o arquivo para o Power BI onde criei:

KPIs: Cartões com valores agregados.

Segmentação: Filtros por status de pagamento e período.

Visualização Geográfica: Gráficos de barras comparando o faturamento entre cidades como Fortaleza, São Paulo e Recife.
