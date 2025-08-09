# 📊 Análise de Evasão de Clientes (Churn) – Telecom

Este projeto tem como objetivo analisar a **evasão de clientes** (*Churn*) em uma empresa de telecomunicações, buscando identificar os principais fatores que influenciam o cancelamento de serviços e propor estratégias de retenção.


---
### 🔍 Objetivo da Análise
O *Churn* representa a porcentagem de clientes que cancelam seus serviços em determinado período.  
Entender quais variáveis impactam essa decisão permite criar **ações preventivas** para reduzir a perda de clientes e aumentar a receita.

---
## 🗂 Estrutura do Projeto

1. **Importação e Limpeza de Dados**
   - Carregamento do dataset
   - Tratamento de valores ausentes
   - Padronização de nomes de colunas
   - Conversão de variáveis categóricas para formato numérico

2. **Análise Exploratória de Dados (EDA)**
   - Cálculo da taxa geral de evasão
   - Análise por variáveis categóricas (gênero, contrato, método de pagamento, etc.)
   - Análise por variáveis numéricas (tempo de contrato, total gasto)
   - Visualizações com gráficos de barras

3. **Conclusões e Insights**
   - Identificação de perfis com maior risco de evasão
   - Relação entre variáveis e probabilidade de cancelamento

4. **Recomendações**
   - Estratégias para reduzir a evasão e aumentar a retenção

---

## 📊 Principais Resultados

- **Taxa geral de evasão:** ~26,5% dos clientes.
- Clientes com **contratos mensais** apresentam maior propensão a cancelar.
- **Métodos de pagamento específicos** estão associados a maior evasão.
- Clientes com **menor tempo de contrato** e **baixo gasto total** tendem a sair mais.
- Serviços adicionais como **segurança online** e **backup** ajudam na retenção.

---

## 🛠 Tecnologias Utilizadas

- **Python** (Pandas, NumPy)
- **Matplotlib** e **Seaborn** (visualização)
- **Google Colab** (execução do notebook)

---

## 📄 Dataset
O dataset contém informações demográficas, de serviços contratados e de faturamento dos clientes, incluindo a variável alvo Churn (Evasão).

Dicionário de dados:

customerID → ID único do cliente

Churn → Cancelamento (Yes/No)

gender → Gênero

SeniorCitizen → Idoso (1) ou não (0)

Partner → Possui cônjuge

Dependents → Possui dependentes

tenure → Meses de contrato

PhoneService → Serviço telefônico

MultipleLines → Mais de uma linha

InternetService → Tipo de internet

OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies → Serviços adicionais

Contract → Tipo de contrato

PaperlessBilling → Fatura digital

PaymentMethod → Método de pagamento

Charges.Monthly → Gasto mensal

Charges.Total → Gasto total

### 📌 Autora

<img src="https://github.com/user-attachments/assets/ee1f5e42-ce53-4afe-93d2-ad5a9d2ebdcc" alt="Foto de Perfil" width="150" height="150"/>

Desenvolvido por **[Caroline Cunha]**  

Você pode me encontrar em:  
- [LinkedIn](https://www.linkedin.com/in/carolinecunha92)

Projeto baseado no *Challenge de Data Science* da [Alura](https://www.alura.com.br/)












