# 📊 Análise de Dados — E-commerce

Este projeto realiza uma análise exploratória e estratégica de dados de um e-commerce, utilizando o ecossistema de dados do **Python** para extrair insights de negócio que auxiliam na tomada de decisão.

O foco principal é demonstrar competências em manipulação de dados, limpeza, visualização interativa e interpretação de métricas de performance (KPIs).

---

## 🎯 Objetivos da Análise

* **Comportamento de Vendas:** Entender o fluxo de pedidos e faturamento.
* **Rentabilidade:** Identificar quais categorias geram maior receita.
* **Ticket Médio:** Analisar o valor médio gasto por pedido em diferentes segmentos.
* **Sazonalidade:** Avaliar a evolução do faturamento ao longo do tempo.
* **Eficiência Operacional:** Explorar o status dos pedidos e gargalos logísticos.

---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** Python 3.x
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização de Dados:** Plotly (Gráficos interativos)
* **Ambiente:** Jupyter Notebook

---

## 🗂️ Estrutura do Projeto

```text
📁 analise-ecommerce
│
├── 📓 analise_base.ipynb       # Exploração inicial e limpeza (Data Cleaning)
├── 📓 analise_final.ipynb      # Geração de insights e visualizações finais
├── 📄 ecommerce.csv            # Dataset utilizado no projeto
├── 📄 requirements.txt         # Dependências para reprodução do ambiente
├── 🖼️ faturamento_categoria.png # Visualização de receita
└── 📄 README.md                # Documentação do projeto
```
---

## 🔍 Processo de Análise

1. Preparação dos Dados (analise_base.ipynb)
Nesta etapa, o foco foi garantir a integridade dos dados (Data Wrangling):

Leitura e inspeção da estrutura dos dados.

Tratamento de valores nulos e validação de colunas.

Conversão de formatos de data para análises temporais.

Exploração inicial de categorias, estados e métodos de pagamento.

2. Análise de Negócio (analise_final.ipynb)
Transformação de dados brutos em conhecimento estratégico através de métricas principais:

Distribuição de Status: Avaliação da eficiência das entregas.

Faturamento por Categoria: Identificação dos pilares de receita.

Ticket Médio: Entendimento do perfil de consumo por segmento.

Evolução Temporal: Análise de crescimento mês a mês.

## 💡 Principais Insights

Volume vs. Valor: Algumas categorias concentram alto faturamento mesmo com ticket médio menor, indicando grande volume de vendas.

Perfil de Consumo: O ticket médio varia significativamente entre categorias, revelando diferentes perfis de comportamento de compra.

Sazonalidade: O faturamento apresenta variações ao longo do tempo, sugerindo padrões que podem ser explorados em campanhas de marketing.

Saúde Logística: A maioria dos pedidos possui status "entregue", indicando uma operação logística saudável.

## 🚀 Como Executar o Projeto

Instale as dependências:

```Bash
pip install -r requirements.txt
```

Execute os Notebooks: Siga a ordem lógica para garantir que os dados sejam processados corretamente:

analise_base.ipynb

analise_final.ipynb

## 🗂️ Fonte dos Dados

Base de dados de e-commerce utilizada para fins educacionais e de portfólio, simulando um cenário real de análise de dados.

## 👤 Autor

Carlos Jaquis 