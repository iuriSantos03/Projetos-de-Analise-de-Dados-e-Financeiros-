# 📊 Análise de Dados & Projetos Financeiros

Bem-vindo(a)! 👋  
Este repositório reúne **projetos práticos de Análise de Dados e Finanças**, desenvolvidos com foco em **aprendizado aplicado, resolução de problemas reais e construção de portfólio profissional**.

Aqui você encontrará análises utilizando **Excel, Power BI, Python e SQL**, voltadas principalmente para **finanças corporativas, controle orçamentário, indicadores financeiros e inteligência de negócios (BI)**.

---

## 🚀 Objetivos do Repositório

- Aplicar conceitos de **análise de dados na prática**
- Desenvolver projetos voltados para **finanças, contabilidade e BI**
- Criar um **portfólio sólido para processos seletivos**
- Explorar **visualização de dados, automação e storytelling com dados**

---

## 🧰 Ferramentas & Tecnologias

- 🐍 Python (Pandas, NumPy, Matplotlib, Seaborn)
- 📊 Power BI
- 📈 Excel Avançado
- 🗄 SQL
- ⚙ Power Query
- 🧠 Lógica Analítica & Estatística Aplicada

---

## 📂 Estrutura do Repositório

📁 projetos/
├── 📊 analise_financeira/
├── 📉 controle_orcamentario/
├── 📈 indicadores_kpi/
├── 🧠 exploracao_dados/
└── 📄 relatorios/


---

## 📌 Projetos em Destaque

- 📊 Análise Financeira Empresarial  
- 💰 Controle Orçamentário e Fluxo de Caixa  
- 📉 Análise de Indicadores Financeiros (KPIs)  
- 📈 Dashboards Gerenciais em Power BI  
- 🧠 Exploração e Limpeza de Dados  

---

## 🐍 Exemplo de Código — Análise Financeira em Python

```python
import pandas as pd

# Carregando base de dados
df = pd.read_excel("dados_financeiros.xlsx")

# Criando indicador de margem de lucro
df["Margem_Lucro"] = (df["Lucro Líquido"] / df["Receita"]) * 100

# Estatísticas básicas
print(df.describe())

# Visualizando as primeiras linhas
df.head()
📊 Exemplo — Consulta SQL Financeira
SELECT 
    departamento,
    SUM(receita) AS receita_total,
    SUM(despesa) AS despesa_total,
    SUM(receita) - SUM(despesa) AS lucro
FROM financeiro
GROUP BY departamento
ORDER BY lucro DESC;
📈 Exemplo — Medida DAX no Power BI
Lucro Total = SUM(Financeiro[Receita]) - SUM(Financeiro[Despesa])
🎯 Competências Desenvolvidas
Análise Financeira

Business Intelligence (BI)

Modelagem de Dados

Visualização Estratégica

Pensamento Analítico

Automação de Relatórios

🧠 Em Desenvolvimento
Dashboards avançados em Power BI

Modelagem estatística aplicada à finanças

Projetos com bases públicas reais

Estudos com Machine Learning para análise financeira

🤝 Contato & Networking
📎 LinkedIn: https://www.linkedin.com/in/iuri-jesus-santos/
📧 Email: dejesusdossantosiuri@gmail.com
