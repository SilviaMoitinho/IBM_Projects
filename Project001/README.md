# 📊 Personal Expense Analysis 🇬🇧

Project developed in **Python** and **Pandas**, as a complement to studies in the **IBM Data Science** course.

## 🎯 Goal

Analyze a fictional personal expense dataset, covering 6 months and 5 different categories, to answer questions such as:

- What was the total amount spent in the period?
- Which category consumes the most of the budget?
- How do expenses vary from month to month?

## 🛠️ Technologies used

- **Python 3**
- **Pandas** — data reading, cleaning and analysis (`read_csv`, `groupby`, `.dt`)
- **Matplotlib** — data visualization (bar chart and line chart)
- **Jupyter Notebook** — interactive development

## 📁 Project structure

```
Projeto001/
├── despesas.csv              # fictional expense data (date, category, amount)
├── analise_despesas.ipynb    # notebook with the full analysis
└── README.md
```

## 📄 About the data

The `despesas.csv` file contains fictional expenses with three columns:

| Column      | Description                                              |
|-------------|------------------------------------------------------------|
| `data`      | Date of the expense (format YYYY-MM-DD)                    |
| `categoria` | Expense category (Food, Transport, Leisure, Bills, Health) |
| `valor`     | Amount spent, in euros                                      |

## 🔍 Analysis steps

1. **Load the data** with `pd.read_csv()`
2. **Explore the structure** with `df.info()`, checking data types
3. **Calculate total expenses** with `.sum()`
4. **Group by category** with `.groupby("categoria")`, identifying which one consumes the most of the budget (`.idxmax()`)
5. **Convert the date column** to `datetime` type with `pd.to_datetime()`
6. **Extract the month** from each expense with `.dt.month`
7. **Group by month** to observe how expenses evolve over time
8. **Visualize the results** with bar and line charts (Matplotlib)

## 📈 Key results

- Total spent in the period: **€2,483.30**
- Category with the highest share of the budget: **Bills** (Contas)
- Month with the highest spending: **May**, with **€540.50**

## 🚀 How to run

1. Clone this repository
2. Install the dependencies:
   ```
   pip install pandas matplotlib jupyter
   ```
3. Open `analise_despesas.ipynb` in Jupyter Notebook or VS Code (with the Jupyter extension)
4. Run the cells in order

## 📌 About

Project created as part of the practical studies for the **IBM Data Science** course, focused on using the Pandas library for exploratory data analysis.

---

# 📊 Análise de Despesas Pessoais 🇵🇹

Projeto desenvolvido em **Python** e **Pandas**, como complemento aos estudos do curso **IBM Data Science**.

## 🎯 Objetivo

Analisar um conjunto de despesas pessoais fictícias, cobrindo 6 meses e 5 categorias diferentes, para responder a perguntas como:

- Qual foi o total gasto no período?
- Qual categoria consome mais do orçamento?
- Como os gastos variam mês a mês?

## 🛠️ Tecnologias utilizadas

- **Python 3**
- **Pandas** — leitura, limpeza e análise dos dados (`read_csv`, `groupby`, `.dt`)
- **Matplotlib** — visualização de dados (gráfico de barras e gráfico de linha)
- **Jupyter Notebook** — desenvolvimento interativo

## 📁 Estrutura do projeto

```
Projeto001/
├── despesas.csv              # dados fictícios de despesas (data, categoria, valor)
├── analise_despesas.ipynb    # notebook com toda a análise
└── README.md
```

## 📄 Sobre os dados

O ficheiro `despesas.csv` contém despesas fictícias com três colunas:

| Coluna     | Descrição                                              |
|------------|---------------------------------------------------------|
| `data`     | Data da despesa (formato AAAA-MM-DD)                    |
| `categoria`| Categoria do gasto (Alimentação, Transporte, Lazer, Contas, Saúde) |
| `valor`    | Valor gasto, em euros                                    |

## 🔍 Etapas da análise

1. **Carregamento dos dados** com `pd.read_csv()`
2. **Exploração da estrutura** com `df.info()`, verificando os tipos de dados
3. **Cálculo do total de gastos** com `.sum()`
4. **Agrupamento por categoria** com `.groupby("categoria")`, identificando qual consome mais do orçamento (`.idxmax()`)
5. **Conversão da coluna de data** para o tipo `datetime` com `pd.to_datetime()`
6. **Extração do mês** de cada despesa com `.dt.month`
7. **Agrupamento por mês** para observar a evolução dos gastos ao longo do tempo
8. **Visualização dos resultados** com gráficos de barras e de linha (Matplotlib)

## 📈 Principais resultados

- Total gasto no período: **2.483,30€**
- Categoria com maior peso no orçamento: **Contas**
- Mês com maior gasto: **maio**, com **540,50€**

## 🚀 Como executar

1. Clone este repositório
2. Instale as dependências:
   ```
   pip install pandas matplotlib jupyter
   ```
3. Abra o `analise_despesas.ipynb` no Jupyter Notebook ou no VS Code (com a extensão Jupyter)
4. Execute as células em ordem

## 📌 Sobre

Projeto criado como parte dos estudos práticos do curso **IBM Data Science**, com foco no uso da biblioteca Pandas para análise exploratória de dados.
