# 📊 Telecom Customer Behavior Analysis  
## EDA of Megaline Prepaid Plans (Surf vs. Ultimate)

### Overview  
This project analyzes customer usage behavior from **Megaline**, focusing on calls, messages, and internet data across two prepaid plans.  
The main objective is to determine **which plan generates more revenue** and understand how user behavior differs between Surf and Ultimate.

Complete analysis in:  
📄 **`megaline_analysis.ipynb`**

---

## 📌 Project Context — Sprint 4 (Real Telecom Case Study)

This project was developed as part of **Sprint 4: Statistical Data Analysis**, a real-world analytical case study.  
The challenge simulates working as an analyst at **Megaline**, where the commercial team needs to identify **which prepaid plan performs better financially** to guide advertising budget allocation.

You are provided with data from **500 customers**, including:  
- who they are  
- where they live  
- which plan they use  
- how many calls, messages and internet sessions they made in 2018  

The task includes:  
1. Preparing and cleaning five datasets (users, calls, messages, internet, plans)  
2. Aggregating usage monthly per customer  
3. Computing revenue based on plan limits and extra fees  
4. Analyzing customer behavior statistically  
5. Testing hypotheses such as:  
   - *Is the average revenue different between Surf and Ultimate?*  
   - *Does the NY–NJ region differ from other regions?*  
6. Delivering a final conclusion with business insights  

This Sprint evaluates real analytical skills: data cleaning, EDA, statistics, hypothesis testing, visualization, and communication of results.

---

## Objectives

- Clean and preprocess all datasets  
- Aggregate monthly usage per customer  
- Calculate monthly revenue based on plan limits  
- Compare Surf vs. Ultimate performance  
- Run statistical tests to validate differences  
- Provide business insights for marketing and pricing decisions  

---

## Data Sources

- **Calls:** duration and date  
- **Messages:** SMS history  
- **Internet:** MB used per session  
- **Plans:** prices, limits and extra fees  
- **Users:** plan type, city, registration and churn data  

---

## Key Steps

### ✔️ Data Preparation  
- Date parsing  
- Duplicate and error removal  
- Feature creation: `month`, `gb_used`, `status`

### ✔️ Monthly Aggregation  
Unified dataset per user/month (minutes, messages, GB, plan data, revenue).

### ✔️ Analysis Highlights  
- Surf users show high variability and frequent limit exceedance  
- Ultimate users generate consistent, predictable revenue  
- Statistical tests confirm **Ultimate > Surf** in mean revenue  
- Regional behavior differences also significant  

---

## Tools  
Python • pandas • numpy • matplotlib • seaborn • scipy • Jupyter Notebook

---

## Summary  
Ultimate is the most stable and profitable plan. Surf users generate extra fees but with greater variability.  
This project demonstrates full EDA workflow: cleaning → feature engineering → aggregation → visualization → hypothesis testing → insights.

---

---

# 📊 Análise de Comportamento dos Clientes Telecom  
## EDA dos Planos Pré-Pagos Megaline (Surf vs. Ultimate)

### Visão Geral  
Este projeto analisa o comportamento de uso dos clientes da **Megaline**, considerando chamadas, mensagens e consumo de internet entre os planos Surf e Ultimate.  
O objetivo principal é identificar **qual plano gera mais receita** e entender como os usuários se comportam em cada plano.

Análise completa em:  
📄 **`megaline_analysis.ipynb`**

---

## 📌 Contexto do Projeto — Sprint 4 (Estudo de Caso Real)

Este trabalho faz parte da **Sprint 4: Análise Estatística de Dados**, um estudo de caso baseado em um cenário real de negócios.  
A Megaline quer descobrir **qual plano pré-pago é mais rentável** para direcionar melhor o orçamento de publicidade.

Você recebe dados de **500 clientes**, incluindo:  
- perfil e localização  
- plano contratado  
- chamadas, mensagens e sessões de internet ao longo de 2018  

As etapas incluem:  
1. Preparação e limpeza dos cinco datasets  
2. Agregação mensal por cliente  
3. Cálculo da receita com base nas franquias e tarifas excedentes  
4. Análise estatística do comportamento do usuário  
5. Testes de hipóteses como:  
   - *Surf x Ultimate: qual gera mais receita?*  
   - *Clientes de NY–NJ gastam diferente das outras regiões?*  
6. Conclusão geral com recomendações de negócio  

A Sprint avalia competências fundamentais de um analista: limpeza, EDA, estatística, testes de hipótese, visualização e interpretação.

---

## Objetivos

- Limpar e pré-processar os dados  
- Agregar o uso mensal por cliente  
- Calcular a receita mensal  
- Comparar os planos Surf e Ultimate  
- Testar estatisticamente diferenças de receita  
- Criar insights acionáveis para decisões comerciais  

---

## Fontes de Dados

- **Chamadas:** duração e data  
- **Mensagens:** registros de SMS  
- **Internet:** MB por sessão  
- **Planos:** franquias, valores e taxas extras  
- **Usuários:** cidade, plano, registro e churn  

---

## Principais Etapas

### ✔️ Preparação dos Dados  
- Conversão de datas  
- Remoção de duplicatas e erros  
- Criação de features: `month`, `gb_used`, `status`

### ✔️ Agregação Mensal  
Dataset consolidado com minutos, mensagens, GB e receita por mês/usuário.

### ✔️ Resultados  
- Usuários Surf variam muito e excedem limites com frequência  
- Ultimate garante receita estável  
- Testes estatísticos confirmam: **Ultimate > Surf**  
- Diferenças regionais também são significativas  

---

## Ferramentas  
Python • pandas • numpy • matplotlib • seaborn • scipy • Jupyter Notebook

---

## Resumo  
Ultimate é o plano mais estável e lucrativo, enquanto Surf depende fortemente de excedentes.  
O projeto demonstra todo o fluxo analítico: limpeza → engenharia → agregação → visualização → testes → insights.
