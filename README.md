🔎 Metodologia Aplicada
Durante o desenvolvimento do projeto, foram aplicadas as seguintes etapas de forma estruturada:

📌 1. Definição clara do problema e hipóteses iniciais
Problema central:
Analisar os fatores que influenciam as avaliações (pontuações de review) dadas pelos clientes em uma plataforma brasileira de e-commerce.

Justificativa:
As avaliações refletem diretamente a percepção de qualidade do serviço, logística, experiência de compra e satisfação geral, impactando diretamente a retenção de clientes e as estratégias de negócio.

Hipóteses iniciais:

O tempo de entrega influencia diretamente a nota de avaliação.

Cancelamentos ou atrasos nos pedidos tendem a resultar em notas mais baixas.

Pedidos com status delivered tendem a apresentar avaliações mais favoráveis.

Pode haver concentração de notas em torno de 4 e 5 (possível desbalanceamento de classes).

📌 2. Leitura e compreensão dos dados
Carregamento dos datasets originais extraídos do Kaggle: olist_orders_dataset.csv e olist_order_reviews_dataset.csv.

Identificação e análise dos atributos disponíveis.

Mapeamento das relações entre as tabelas (chaves de junção: order_id).

Verificação inicial de estrutura, tipos de dados e integridade dos registros.

📌 3. Análise exploratória com visualizações e estatísticas descritivas
Análise descritiva das variáveis numéricas e categóricas.

Visualizações gráficas:

Histogramas e countplots da distribuição de review_score.

Boxplots para identificar dispersão e outliers.

Gráficos de barras para visualizar o comportamento do order_status.

Identificação de padrões de concentração de notas altas e possíveis desbalanceamentos.

📌 4. Identificação e tratamento de valores ausentes e inconsistências
Análise detalhada de dados faltantes em cada coluna.

Avaliação do impacto dos valores ausentes.

Remoção de registros incompletos para manter a qualidade da análise.

📌 5. Pré-processamento e limpeza dos dados
Seleção dos atributos relevantes (order_status, order_purchase_timestamp, review_score).

Exclusão de variáveis não necessárias.

Conversão de tipos de dados e padronização de formatos.

Preparação final dos dados para etapas futuras de modelagem preditiva.

📌 6. Documentação detalhada e cumprimento do checklist
Registro completo de cada etapa no notebook (Google Colab).

Organização e explicação de cada bloco de código.

Cumprimento integral do checklist de avaliação da disciplina.

✅ Checklist — Definição do Problema
📌 Descrição do problema
Investigar os fatores que influenciam as avaliações (notas de review) dadas pelos clientes em um e-commerce brasileiro. As avaliações refletem eficiência logística, cumprimento de prazos, qualidade do atendimento e satisfação geral do consumidor.

📌 Tipo de problema
Aprendizado supervisionado (classificação).

Variável alvo: review_score (conhecida e categórica).

📌 Hipóteses iniciais
Status do pedido influencia diretamente a nota.

Entregas no prazo recebem notas mais altas.

Cancelamentos e atrasos impactam negativamente.

Concentração de notas entre 4 e 5.

Predomínio de avaliações positivas.

📌 Restrições e condições de seleção dos dados
Dados obtidos do Brazilian E-Commerce Public Dataset by Olist (Kaggle).

Utilização de olist_orders_dataset.csv e olist_order_reviews_dataset.csv.

Apenas registros com avaliações foram considerados.

Dados anonimizados, sem informações pessoais sensíveis.

Registros com valores ausentes foram removidos.

📌 Definição dos atributos
Atributos de olist_orders_dataset.csv
Atributo	Descrição	Tipo de dado
order_id	Identificador único do pedido	Categórico
customer_id	Identificador do cliente	Categórico
order_status	Status do pedido (ex.: delivered, canceled)	Categórico
order_purchase_timestamp	Data e hora da compra	Data/Hora

Atributos de olist_order_reviews_dataset.csv
Atributo	Descrição	Tipo de dado
review_id	Identificador único da avaliação	Categórico
order_id	Identificador do pedido (chave de junção)	Categórico
review_score	Nota de avaliação do cliente (de 1 a 5)	Numérico (Ordinal)

🚀 Execução
Projeto desenvolvido integralmente no Google Colab.

👨‍🎓 Autor
Abraão Nazário
