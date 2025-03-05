# **Case de Análise de Dados em um Marketplace de Eletrônicos**

## Descrição

Este projeto tem como objetivo analisar dados de um **marketplace de eletrônicos**, avaliando indicadores financeiros e operacionais para embasar decisões estratégicas. Foram utilizadas técnicas de **SQL para consultas em banco de dados** e **Power BI para visualização interativa**.

## Estrutura do Projeto

1. **Carregamento e Processamento dos Dados**
   - Importação de arquivos CSV (Pedidos, Produtos e Clientes)
   - Estruturação dos dados em DataFrames para facilitar a análise

2. **Armazenamento Temporário em Banco de Dados**
   - Criação de um banco de dados SQLite em memória
   - Inserção das tabelas no banco para consultas SQL

3. **Análise Exploratória dos Dados (EDA) para responder às perguntas de negócio**

   - Nesta etapa, serão analisados os principais indicadores do marketplace, permitindo entender padrões de compra, lucratividade e comportamento dos clientes. As seguintes questões serão respondidas:

     ✔**Qual foi o faturamento mensal do marketplace no período analisado?**
     
     ✔**Qual foi o lucro mensal do marketplace no período analisado?**
          
     ✔**Qual foi a margem de lucro média mensal considerando o custo dos produtos?**
          
     ✔**Qual é a taxa de cancelamento mensal de pedidos?**
          
     ✔**Quais são os três produtos mais vendidos e seus respectivos faturamentos?**
          
     ✔**Quais são os métodos de pagamento mais utilizados?**
          
     ✔**Quais estados geraram mais vendas?**
          
     ✔**Quantos clientes realizaram mais de uma compra?**

   - Além disso, serão avaliados aspectos como a sazonalidade das vendas, a rentabilidade dos produtos e a distribuição geográfica dos clientes, fornecendo insights para otimizar as estratégias do marketplace.


4. **Criação de Dashboards e Recomendações**
   - Visualização dos resultados no Power BI
   - Desenvolvimento de insights estratégicos com base nos dados
   - Sugestão de campanhas promocionais e ajustes na precificação

## Dashboard Interativo no Power BI

🔗 [Acesse o dashboard publicado no Power BI](https://app.powerbi.com/view?r=eyJrIjoiNGVlNTQ5YTctMTA2ZC00ZTQ5LWFmNWQtMWQ0NTdhYTc3YTA2IiwidCI6IjM1NWM1NGI0LTc3ZjktNDI0NS1hMzAwLTYxYzJhYWM4M2RmYSJ9)  

## Tecnologias Utilizadas

- **📌 SQL (SQLite)** → Manipulação e extração de dados
- **📌 Python (Pandas, SQLite3)** → Processamento e estruturação dos dados
- **📌 Power BI** → Visualização interativa e criação de dashboards

## Arquivos no Repositório

- `case_resolucao.ipynb` → Notebook com análise de dados e consultas SQL
- `dashboard_case.pbix` → Arquivo do Power BI contendo o dashboard interativo
- `Relatório Interpretativo.pdf` → Relatório final com insights e recomendações

---

✍️ **Autor**: [Carolyne Soares](https://github.com/CarolyneSoares)  
📅 **Última atualização:** Março/2025

