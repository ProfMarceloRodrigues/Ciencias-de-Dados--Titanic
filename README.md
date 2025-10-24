# Ciencias-de-Dados--Titanic  

# 🛳️ Análise do Titanic — Parte 1

Este projeto tem como objetivo realizar uma **análise exploratória de dados (EDA)** sobre o clássico dataset **Titanic - Machine Learning from Disaster**, disponível no [Kaggle](https://www.kaggle.com/competitions/titanic).

A análise faz parte de um estudo de **Ciência de Dados e Machine Learning**, abordando as etapas iniciais do processo: importação, exploração e tratamento dos dados.

---

## 📊 Objetivos do Projeto

- Compreender a estrutura da base de dados do Titanic  
- Identificar variáveis relevantes para análise preditiva (como sobrevivência dos passageiros)  
- Detectar e tratar valores ausentes  
- Explorar distribuições, correlações e padrões nos dados  
- Preparar a base para modelagem futura

---

## 🧩 Base de Dados

O dataset contém informações de passageiros do Titanic, incluindo:
- Nome, sexo e idade  
- Classe de viagem (1ª, 2ª, 3ª)  
- Número de familiares a bordo  
- Valor da passagem (`Fare`)  
- Porto de embarque (`Embarked`)  
- Status de sobrevivência (`Survived`)

---

## ⚙️ Etapas Realizadas

1. **Importação dos dados**
   - Carregamento dos arquivos `titanic_train.csv` e `titanic_test.csv` usando `pandas`.

2. **Análise inicial com ydata-profiling**
   - Geração de relatórios automáticos com a biblioteca [`ydata-profiling`](https://github.com/ydataai/ydata-profiling) para identificar outliers, tipos de dados e estatísticas descritivas.

3. **Verificação de tipos e valores nulos**
   - Análise das colunas com `DataFrame.info()`, `dtypes` e `isnull()`.

4. **Tratamento de dados ausentes**
   - Substituição de valores nulos e ajustes em variáveis categóricas.

5. **Visualização e preparação**
   - Preparação da base para futuras etapas de modelagem e machine learning.

---

## 🧠 Principais Insights

- Algumas variáveis apresentam **valores ausentes significativos**, exigindo imputação ou exclusão.  
- As colunas `Age`, `Cabin` e `Embarked` foram as mais críticas em termos de dados faltantes.  
- Observou-se relação entre **classe de viagem**, **sexo** e **probabilidade de sobrevivência** — pontos importantes para modelagem preditiva.

---

## 🧰 Tecnologias Utilizadas

- **Python 3**
- **Pandas**
- **YData Profiling** (antigo Pandas Profiling)
- **Jupyter Notebook**

---

## 🚀 Próximos Passos

- Realizar **feature engineering** (criação de novas variáveis relevantes)  
- Testar diferentes **modelos de machine learning** (Logistic Regression, Random Forest, etc.)  
- Avaliar o desempenho dos modelos com base na acurácia  
- Submeter previsões ao Kaggle

---

## 📁 Estrutura do Projeto



---

## 👨‍💻 Autor

**Marcelo Rodrigues**  
Consultor de Dados e fundador da [Starts Treinamentos & Consultoria](https://www.linkedin.com/in/marcelordasilva/)  
📧 ma23cgl@gmail.com  

---

> Este projeto faz parte de um estudo prático sobre análise de dados e aprendizado de máquina, utilizando o dataset Titanic como base introdutória para problemas de classificação.

