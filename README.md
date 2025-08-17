# Credit Card Fraud Detection

## Descrição do Projeto
Este projeto realiza **detecção de fraudes em transações financeiras** usando o dataset [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) do Kaggle.  
O objetivo é identificar transações fraudulentas utilizando **Machine Learning**, fornecendo métricas confiáveis e visualizações claras para análise de risco.


## Dataset
- **Fonte:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- Contém **284.807 transações**, sendo apenas **492 fraudes** (classe desbalanceada).  
- **Atenção:** Os arquivos CSV **não estão incluídos no repositório** por serem muito grandes (>100MB).  

### Como adicionar os dados localmente
1. Baixe o arquivo `creditcard.csv` do Kaggle.  
2. Crie a pasta `data/raw/` no seu projeto.  
3. Coloque o CSV dentro desta pasta: `data/raw/creditcard.csv`.  
4. Se você fizer limpeza de dados e salvar um novo CSV, coloque em `data/clean/creditcard_clean.csv`.

## Como usar
1. Instale o ambiente virtual (opcional, mas recomendado):
   ```powershell
   python -m venv .venv
   .venv\Scripts\Activate.ps1  # Windows PowerShell

Instale as dependências: pip install -r requirements.txt
Abra o Jupyter Notebook: jupyter notebook


Execute os notebooks na ordem:
01-EDA.ipynb
02-cleaning.ipynb
03-modeling.ipynb
04-dashboard.ipynb

Dependências

Python >= 3.10
Pandas, Numpy, Matplotlib, Seaborn
Scikit-learn
Jupyter Notebook

Autor
Geise Ramos
   

   


