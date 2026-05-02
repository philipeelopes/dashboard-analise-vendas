📊 Dashboard de Análise de Vendas
📌 Visão Geral

Este projeto consiste no desenvolvimento de um Dashboard de Análise de Vendas utilizando Power BI, com foco na extração, tratamento, modelagem e visualização de dados para apoio à tomada de decisão.

O dashboard apresenta os principais indicadores de desempenho comercial, permitindo uma análise clara e intuitiva mesmo para usuários sem conhecimento técnico em dados.

## 📸 Preview do Dashboard

![Dashboard](dash principal)

🎯 Objetivo do Projeto
Analisar o desempenho de vendas ao longo do tempo
Identificar os produtos com maior impacto no faturamento
Avaliar a concentração de receita (Princípio de Pareto)
Visualizar a distribuição das vendas por região
Aplicar boas práticas de modelagem, DAX e design de dashboards
🗂️ Fonte dos Dados

Base de dados fictícia de vendas, contendo as seguintes informações:

Data da venda
Produto
Região
Quantidade vendida
Valor total da venda
Vendedor

Os dados foram tratados e modelados diretamente no Power BI.

🧱 Modelagem de Dados
Criação de Tabela Calendário para análises temporais
Relacionamento entre tabela fato (vendas) e dimensões
Utilização de boas práticas de modelagem (modelo estrela)
Uso correto de cardinalidade e direção de filtros
📐 Principais Métricas (DAX)

O projeto utiliza medidas em DAX, com foco em cálculos claros e eficientes.

Principais métricas desenvolvidas:
Total de Vendas
Quantidade de Vendas
Quantidade Vendida
Ticket Médio
Vendas por Mês
Vendas no Mês Anterior
Diferença de Vendas (MoM)
Variação Percentual (MoM)
Vendas Acumuladas
Ranking de Produtos
Percentual Acumulado (Pareto)

📌 As medidas foram desenvolvidas utilizando funções como:
SUM, CALCULATE, FILTER, ALL, RANKX, DIVIDE, DATEADD, SELECTEDVALUE.

📊 Visualizações do Dashboard
🔹 KPIs
Total de Vendas
Quantidade de Vendas
Ticket Médio
Quantidade de Vendedores
🔹 Gráficos
Vendas ao longo do tempo (Gráfico de linha)
Top 5 Produtos mais vendidos (Gráfico de barras)
Pareto dos Produtos (Tabela com % acumulada)
Total de Vendas por Região (Gráfico de rosca)

Os visuais foram escolhidos com foco em clareza, leitura rápida e storytelling de dados.

🎨 Design do Dashboard
Layout e identidade visual desenvolvidos no Figma
Uso de paleta de cores neutra (tons de azul) para melhor legibilidade
Organização visual baseada em hierarquia da informação
Design pensado para usuários não técnicos

Após o design no Figma, o layout foi replicado e ajustado no Power BI.

🔎 Filtros e Interatividade

O dashboard permite análises dinâmicas por meio de filtros:

Período
Produto
Região

Os filtros foram organizados de forma a não poluir o layout principal, mantendo foco nos indicadores.

🧠 Principais Insights
Poucos produtos concentram a maior parte do faturamento (Pareto)
Existe variação mensal significativa nas vendas
Determinadas regiões concentram a maior participação de receita
O produto líder possui forte impacto no resultado geral
🛠️ Ferramentas Utilizadas
Power BI (Modelagem, DAX, Visualizações)
DAX (Cálculo de métricas e indicadores)
Figma (Design do dashboard)
Excel (Organização inicial dos dados)
GitHub (Versionamento e portfólio)
📚 Aprendizados
Construção de medidas DAX do básico ao intermediário
Criação de tabela calendário e análises temporais
Aplicação prática de Pareto (80/20)
Boas práticas de visualização de dados
Importância da documentação em projetos de dados
👤 Autor

Philipe da Rosa Lopes
Estudante de Ciência da Computação | Analista de Dados Júnior

🔗 LinkedIn: (www.linkedin.com/in/philipe-lopes-9abba5320)
🔗 GitHub: (adicione aqui)

✅ Status do Projeto

✔ Projeto finalizado
✔ Pronto para portfólio

🏁 Consideração final

Este projeto foi desenvolvido com foco em aprendizado prático, clareza de comunicação e boas práticas do mercado, sendo ideal para demonstração de habilidades em processos de Análise de Dados e Business Intelligence.
