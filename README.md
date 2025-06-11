
# 🛒 MVP - Análise Exploratória e Pré-Processamento de Dados

Este repositório contém o projeto de análise exploratória e pré-processamento de dados desenvolvido como parte da disciplina **Análise Exploratória e Pré-Processamento de Dados**.

🔎 Metodologia Aplicada
Durante o desenvolvimento do projeto, foram aplicadas as seguintes etapas de forma estruturada:

📌 1. Definição clara do problema e hipóteses iniciais
Problema central: Analisar os fatores que influenciam as avaliações (pontuações de review) dadas pelos clientes em uma plataforma brasileira de e-commerce.

Justificativa: Avaliações de clientes refletem diretamente a percepção de qualidade do serviço, logística, experiência de compra e satisfação geral, podendo impactar a retenção de clientes e a estratégia de negócios.

Hipóteses iniciais:

O tempo de entrega influencia diretamente a nota de avaliação.

Cancelamentos ou atrasos nos pedidos tendem a resultar em notas mais baixas.

Pedidos com status "delivered" tendem a apresentar avaliações mais favoráveis.

Pode haver concentração de notas em torno de 4 e 5 (possível desbalanceamento).

📌 2. Leitura e compreensão dos dados
Carregamento dos datasets originais extraídos do Kaggle: olist_orders_dataset.csv e olist_order_reviews_dataset.csv.

Identificação e análise dos atributos disponíveis em cada arquivo.

Mapeamento das relações entre as tabelas (chaves de junção, como order_id).

Verificação inicial de estrutura, tipos de dados e integridade.

📌 3. Análise exploratória com visualizações e estatísticas descritivas
Análise descritiva das variáveis numéricas e categóricas.

Visualizações gráficas:

Histogramas e countplots da distribuição dos review_score.

Boxplots para identificar dispersão e possíveis outliers nas avaliações.

Gráficos de barras para visualizar o comportamento do order_status (status do pedido).

Identificação de padrões de concentração de notas altas e desbalanceamento das classes.

📌 4. Identificação e tratamento de valores ausentes e inconsistências
Análise detalhada de dados faltantes em cada coluna dos datasets carregados.

Avaliação do impacto dos valores ausentes no processo analítico.

Remoção de registros com dados incompletos que poderiam prejudicar as análises subsequentes.

📌 5. Pré-processamento e limpeza dos dados
Seleção dos atributos relevantes para a análise (como status do pedido, data de compra e nota de avaliação).

Exclusão de variáveis irrelevantes para o objetivo do projeto.

Conversão de tipos de dados e padronização de formatos quando necessário.

Preparação do dataset final para etapas posteriores de modelagem e predição.

📌 6. Documentação detalhada das etapas e cumprimento do checklist proposto
Registro textual detalhado de cada etapa dentro do notebook no Google Colab.

Organização do código com blocos de markdown explicativos.

Cumprimento integral do checklist de avaliação exigido pela disciplina, cobrindo análise exploratória, pré-processamento, documentação e organização do código.


## 🚀 Execução

desenvolvido no **Google Colab** 
---

## 👨‍🎓 Autor

Abraão Nazário
