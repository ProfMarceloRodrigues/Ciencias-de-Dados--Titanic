# Titanic - Machine Learning from Disaster

Este projeto apresenta uma análise e modelagem preditiva aplicada ao famoso conjunto de dados *Titanic*. 
O objetivo é explorar os dados, tratar variáveis e aplicar diferentes algoritmos de Machine Learning para prever 
quais passageiros sobreviveram ao desastre.

## 🧭 Estrutura do Projeto

```
.
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
├── data/
│   ├── train.csv
│   └── test.csv
└── notebooks/
    └── Análise_do_Titanic_-_Parte_5_-_Arquivo_Final.ipynb
```

## ⚙️ Etapas Realizadas

- Importação e limpeza de dados
- Engenharia de atributos (tratamento de nulos, encoding, scaling)
- Visualizações com matplotlib e seaborn
- Treinamento e comparação de modelos (Regressão Logística, Random Forest, MLP)
- Avaliação com métricas de desempenho e matriz de confusão

## 🧠 Modelos Aplicados

- `LogisticRegression`
- `RandomForestClassifier`
- `MLPClassifier`

## 📦 Dependências

As principais bibliotecas utilizadas no projeto estão listadas em `requirements.txt`.

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/titanic-ml.git
   cd titanic-ml
   ```

2. Crie e ative o ambiente virtual:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   .venv\Scripts\activate   # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute o notebook no Jupyter:
   ```bash
   jupyter notebook
   ```

5. Abra o arquivo `notebooks/Análise_do_Titanic_-_Parte_5_-_Arquivo_Final.ipynb` e execute todas as células.

## 📈 Resultados

Os resultados incluem comparação de desempenho entre os modelos e análise visual das predições.

## 🧾 Licença

Este projeto é licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

**Marcelo Rodrigues**  
Consultor e Fundador da Starts Treinamentos & Consultoria  
[LinkedIn](https://www.linkedin.com/in/marcelordasilva/)  
E-mail: ma23cgl@gmail.com
