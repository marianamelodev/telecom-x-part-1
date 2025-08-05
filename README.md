# 📊 Telecom X - Análise de Evasão de Clientes (Churn)

Este projeto foi desenvolvido como parte do desafio da formação **One Next Education - Alura**, com o objetivo de entender os motivos que levam clientes a cancelarem os serviços da Telecom X e propor estratégias para reduzir a evasão.

---

## 🧠 Objetivo

Analisar dados fornecidos pela empresa **Telecom X**, entender os principais fatores relacionados ao cancelamento de clientes (churn) e gerar insights valiosos para ajudar a empresa a reter mais clientes.

---

## 🛠️ Habilidades Praticadas

- Extração de dados via API (JSON)
- Manipulação de dados com **Pandas**
- Limpeza e tratamento de dados (ETL)
- Criação de novas variáveis
- Visualização de dados com **Matplotlib** e **Seaborn**
- Análise Exploratória de Dados (EDA)
- Elaboração de relatório estratégico

---

## 🔗 Fonte de Dados

- Dados extraídos de uma **API JSON** fornecida no desafio.
- Dicionário de dados com descrição das variáveis (utilizado como guia para interpretação).

---

## 🗂️ Estrutura do Projeto

O projeto foi realizado em um **Jupyter Notebook**, com as seguintes seções:

### 1. Introdução  
Breve explicação sobre o problema de churn e os objetivos da análise.

### 2. Importação dos Dados  
Uso da biblioteca `requests` para coletar os dados diretamente da API, convertendo-os em um `DataFrame` com Pandas.

### 3. Exploração Inicial dos Dados  
Verificação de colunas, tipos, estatísticas básicas e entendimento do dicionário de dados.

### 4. Limpeza e Tratamento  
Remoção de duplicatas, tratamento de valores nulos e inconsistências em variáveis categóricas.

### 5. Criação de Nova Coluna  
Adição da coluna `Contas_Diarias`, calculada a partir do `TotalGasto / 30`, para observar o comportamento diário de consumo.

### 6. Análise Descritiva  
Cálculo de métricas estatísticas para entender melhor a distribuição dos dados.

### 7. Análise do Churn  
Visualização da proporção de clientes que cancelaram o serviço em relação aos que permaneceram.

### 8. Churn x Variáveis Categóricas  
Análise de variáveis como Gênero, Tipo de Contrato e Método de Pagamento em relação ao churn.

### 9. Churn x Variáveis Numéricas  
Estudo da relação entre churn e variáveis como Total Gasto, Tempo de Contrato e Contas Diárias.

### 10. Conclusões e Recomendações  
Resumo dos principais achados, insights estratégicos e sugestões para a empresa reduzir a evasão de clientes.

---

## 📌 Principais Insights

- **Contratos mensais** estão fortemente associados a uma maior taxa de churn.
- Clientes que gastam menos tendem a cancelar mais.
- **Métodos de pagamento automáticos** apresentaram menor taxa de evasão.
- O churn é mais comum nos primeiros meses do contrato.

---

## ✅ Recomendações Estratégicas

- Incentivar a migração para **contratos anuais** com benefícios.
- Criar ofertas ou bonificações para **clientes novos nos primeiros 3 meses**.
- Monitorar de perto clientes com **baixo consumo mensal**.
- Estimular o uso de **pagamento automático** com descontos ou vantagens.

---

## 📎 Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Requests
- Jupyter Notebook / Google Colab

---

## 🚀 Resultado

Ao final da análise, foi possível identificar padrões importantes no comportamento dos clientes e sugerir ações práticas para ajudar a Telecom X a reduzir o churn e aumentar a retenção.

---

## 📁 Como Executar

1. Clone este repositório
2. Abra o notebook `telecom_churn_analysis.ipynb` no Jupyter ou Google Colab
3. Execute as células sequencialmente

---

## ✍️ Autoria

Projeto realizado por **Mariana Melo** como parte da formação **One Next Education – Alura**.

