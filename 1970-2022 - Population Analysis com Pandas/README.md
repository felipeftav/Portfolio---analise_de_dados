# Análise da População Mundial (1970–2022)

Este projeto realiza uma **análise exploratória de dados** sobre a população mundial, utilizando dados de 1970 a 2022. O objetivo é extrair insights relevantes sobre crescimento populacional, distribuição por continentes e outras métricas importantes.

---

##  Fonte dos Dados

O dataset utilizado foi obtido no Kaggle:

- [World Population Dataset (world_population.csv)](https://www.kaggle.com/datasets/asahu40/world-population-dataset)

---

##  Análises Realizadas

A análise foi conduzida em um Jupyter Notebook (`Population_Change_1970_2022.ipynb`) e aborda as seguintes questões:

- Ranking dos **10 países mais populosos** do mundo  
- Identificação dos **5 maiores países por área** (km²)  
- Contagem de países por continente presentes no dataset  
- Cálculo da **população média e mediana de 1970**  
- Crescimento populacional **percentual de cada país entre 1970 e 2022**  
- País com o **maior crescimento populacional absoluto** no período  
- **População total de cada continente** em 2022  
- Países que **tiveram diminuição populacional entre 2020 e 2022**  
- Análise da **correlação entre área do país e população em 2022**  
- **Evolução da população mundial total**, de 1970 a 2022  
- Identificação de **outliers na taxa de crescimento populacional**  
- Ranking dos continentes por **taxa de crescimento média**

---

##  Tecnologias Utilizadas

- **Linguagem**: Python  
- **Bibliotecas**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

##  Como Executar o Projeto

```bash
# Clone o repositório
git clone https://seu-usuario/seu-repositorio.git

# Acesse o diretório
cd seu-repositorio

# Crie e ative um ambiente virtual (opcional mas recomendado)
python -m venv venv
source venv/bin/activate  # no Linux/macOS
venv\Scripts\activate     # no Windows

# Instale as dependências
pip install pandas numpy matplotlib seaborn jupyter

# Abra o Jupyter Notebook
jupyter notebook Population_Change_1970_2022.ipynb
