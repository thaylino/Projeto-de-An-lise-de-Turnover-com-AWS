📌 Descrição:
Este projeto tem como objetivo analisar a taxa de turnover em uma empresa, utilizando serviços da AWS para armazenamento, processamento e visualização de dados.

🚀 Arquitetura do Projeto

1️⃣ Upload de dados no Amazon S3
- O time de RH envia arquivos (CSV/Excel) com informações de colaboradores.

2️⃣ Processamento com AWS Lambda
- Função Lambda é acionada automaticamente quando o arquivo é carregado no S3.
- O script processa os dados (ex.: calcula taxa de turnover, normaliza informações) e salva a saída em uma pasta de output no S3.

3️⃣ Catálogo de dados com AWS Glue
- O AWS Glue Data Catalog organiza o esquema dos arquivos processados, permitindo consultas estruturadas.

4️⃣ Visualização com Amazon QuickSight
- Dashboards interativos apresentam métricas de turnover por período, área ou outros filtros relevantes.
