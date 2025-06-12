# Trabalho Remoto e Presencial: Calculando suas Diferenças e Mostrando o Proveito do Melhor

Este projeto analisa os impactos dos modelos de trabalho remoto e presencial na produtividade e bem-estar de funcionários. Utilizando um dataset sintético com 1000 registros, buscamos entender e comprovar estatisticamente as diferenças entre esses dois estilos de trabalho.

---

## 📌 Objetivo

O principal objetivo é investigar:

- Como o tipo de emprego (remoto ou presencial) afeta a **produtividade** e o **bem-estar** dos funcionários.
- Se há **diferenças estatísticas significativas** entre os grupos.
- Quais correlações existem entre **horas trabalhadas**, **produtividade** e **bem-estar**.

---

## 🗂 Organização dos Arquivos

📁 Projeto/
    
    │
    
    ├── 📁 ArquivoPowerBI/ → Representações gráficas desenvolvidas no Power BI.

    ├── 📁 Documentation/ → Documentação e explicações do projeto.

    ├── 📁 Main/ 

  │ ├── main.ipynb → Script principal da análise em Python.

  │ └── 📁 database/ → Contém o dataset utilizado (.csv).

---

## 📥 Coleta de Dados

Os dados utilizados são sintéticos e foram obtidos no [Kaggle](https://www.kaggle.com/), uma plataforma aberta para datasets e projetos de ciência de dados.

- **Formato:** `.csv`
- **Número de registros:** 1000 funcionários
- **Colunas principais:**
  - `employee_id`
  - `employment_type` (remoto ou presencial)
  - `hours_worked_per_week`
  - `productivity_score`
  - `well_being_score`

---

## 🧹 Limpeza e Preparação de Dados

As etapas de pré-processamento incluíram:

- Padronização de nomes das colunas e valores (uso de `lowercase`).
- Definição de `employee_id` como índice.
- Remoção de linhas com valores nulos (`NaN`).

---

## 🔄 Transformações Realizadas

- Separação dos dados em dois DataFrames: `remote` e `in_office`, para análises comparativas.
- Agregações básicas para cálculo de médias e outras estatísticas descritivas.
- Uso das bibliotecas **Pandas** e **NumPy** para manipulação dos dados.

---

## 📊 Visualização de Dados

Foram utilizados gráficos como:

- **Boxplots** para análise visual de distribuição e apoio ao teste t de médias.
- **Gráficos no Power BI** (barras, pizza, dispersão, área) para reforçar insights de forma visual.

---

## ✅ Conclusões

Com base nas análises e nos testes estatísticos realizados:

- Funcionários **remotos** apresentaram, em média:
  - **+15,45% de produtividade**
  - **+18,44% de bem-estar**
  - **-27,59% de horas trabalhadas por semana** comparado aos presenciais.
- O **teste t** indicou **diferença estatística significativa** entre as médias de produtividade dos dois grupos.
- **Não há correlação significativa** entre:
  - Horas trabalhadas × Produtividade
  - Produtividade × Bem-estar

Esses dados sustentam a conclusão de que o trabalho remoto proporciona maiores benefícios em termos de produtividade e bem-estar.

---

## 🧠 Tecnologias e Bibliotecas Utilizadas

- **Python**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy
- **Power BI**

---

## 🔗 Referências

- [Kaggle](https://www.kaggle.com/)
- [Documentação pandas.melt](https://pandas.pydata.org/docs/reference/api/pandas.melt.html)
- [Documentação seaborn.boxplot](https://seaborn.pydata.org/generated/seaborn.boxplot.html)

---

## 💬 Autor

**Kauê Costa Souza**  
Projeto de análise de dados com foco em produtividade no trabalho.  
Contato: www.linkedin.com/in/kauê-costa-souza-5a510523b; kauekaue960@gmail.com

