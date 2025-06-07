📊 Data Warehouse and Analytics Project
Bem-vindo ao repositório do Data Warehouse and Analytics Project! 🚀
Este projeto demonstra o desenvolvimento de uma solução completa de data warehouse e analytics — desde a ingestão e modelagem dos dados até a geração de insights estratégicos para o negócio.

🏗️ Data Architecture: Medallion Design
A arquitetura adotada segue o padrão moderno Medallion Architecture, dividida em três camadas:

🔸 Bronze Layer: Armazena os dados brutos exatamente como foram extraídos dos sistemas fonte (ERP e CRM) em arquivos .csv, posteriormente carregados no banco de dados SQL Server.

🔹 Silver Layer: Realiza a limpeza, padronização e transformação dos dados. Esta camada torna os dados consistentes e prontos para análise.

⭐ Gold Layer: Contém dados de negócio organizados em modelo estrela (Star Schema), otimizados para relatórios e consultas analíticas.

📖 Projeto - Visão Geral
Este projeto contempla as seguintes etapas:

🔧 Engenharia de Dados (Data Engineering)
Arquitetura de Dados: Planejamento e construção do Data Warehouse baseado na arquitetura Medallion.

Pipelines ETL: Desenvolvimento de processos ETL para extração, transformação e carga dos dados.

Modelagem de Dados: Criação de tabelas fato e dimensão conforme as melhores práticas analíticas.

📊 Análise de Dados (Data Analysis)
Consultas SQL: Elaboração de queries analíticas para gerar KPIs e indicadores de negócio.

Dashboards: Criação de relatórios e dashboards para facilitar a tomada de decisão.

🎯 Público-Alvo e Aplicações
Este projeto é ideal para:

Analistas de Dados

Engenheiros de Dados

Cientistas de Dados

Desenvolvedores SQL

Estudantes de tecnologia e business intelligence

Profissionais em transição para a área de dados

🧰 Ferramentas e Recursos Gratuitos
📁 Dataset: Arquivos .csv representando os dados de ERP e CRM.

🛠️ SQL Server Express: Banco de dados leve e gratuito para testes e desenvolvimento.

🖥️ SQL Server Management Studio (SSMS): Interface gráfica para gerenciamento do banco.

🧠 Draw.io: Utilizado para modelagem de dados e fluxogramas ETL.

📚 Notion: Documentação e acompanhamento do projeto (modelo de projeto disponível).

🐙 GitHub: Versionamento do código, scripts SQL, documentação e colaborações.

📌 Requisitos do Projeto
Etapa 1 – Construção do Data Warehouse (Engenharia)
Objetivo: Consolidar dados de vendas oriundos de dois sistemas (ERP e CRM), preparando-os para análise e geração de insights estratégicos.

Especificações:

Fontes: ERP e CRM via arquivos .csv.

Qualidade de Dados: Tratamento de valores nulos, duplicados e inconsistentes.

Integração: Unificação em um único modelo de dados analítico.

Escopo: Trabalhar apenas com o conjunto de dados mais recente.

Documentação: Explicações claras sobre o modelo de dados para equipes técnicas e de negócios.

Etapa 2 – Análise & Relatórios (Analytics)
Objetivo: Utilizar SQL para criar análises e relatórios que respondam a perguntas-chave do negócio, como:

Quais produtos são mais vendidos?

Quem são os melhores clientes?

Qual o desempenho das equipes de vendas?

Quais regiões apresentam maior faturamento?

📁 Organização do Repositório
plaintext
Copiar
Editar
├── datasets/
│   ├── erp_data.csv
│   └── crm_data.csv
├── sql/
│   ├── create_tables.sql
│   ├── etl_scripts.sql
│   └── reporting_queries.sql
├── diagrams/
│   ├── data_architecture.png
│   └── star_schema_model.drawio
├── documentation/
│   ├── data_dictionary.md
│   └── project_overview.pdf
└── dashboards/
    └── sales_dashboard.pbix

