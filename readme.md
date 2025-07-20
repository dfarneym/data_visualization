# 📈 Análise e Visualização de Dados de Imigração para o Canadá

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-orange?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-red?style=flat&logo=matplotlib)
![Seaborn](https://img.shields.io/badge/Seaborn-purple?style=flat&logo=seaborn)
![Plotly](https://img.shields.io/badge/Plotly-blue?style=flat&logo=plotly)
![Jupyter](https://img.shields.io/badge/Jupyter-orange?style=flat&logo=jupyter)

## 📄 Descrição do Projeto

Este repositório contém um projeto de análise e visualização de dados focado nas tendências de imigração para o Canadá entre os anos de 1980 e 2013. O objetivo principal é transformar dados brutos de imigração em visualizações claras e informativas que possam auxiliar na compreensão dos padrões migratórios, especialmente para pessoas que consideram imigrar do Brasil e de outros países da América do Sul.

O projeto foi desenvolvido como parte de um curso de Data Visualization da Alura em parceria com a Oracle Next Education, com ênfase na criação de gráficos eficazes utilizando bibliotecas Python.

## 📁 Estrutura do Repositório
```
DataVisualization/
├── DataVisualization.ipynb         # O notebook Jupyter com toda a análise e visualizações
├── imigrantes_canada.csv           # Conjunto de dados utilizado no projeto
├── imigracao_brasil_canada.png     # Gráfico de linha da imigração do Brasil para o Canadá (Matplotlib)
├── imigracao_america_sul.png       # Gráfico de barras com destaque para o Brasil (Matplotlib/Seaborn)
└── imigracao_america_sul.html      # Gráfico interativo da imigração da América do Sul (Plotly)
└── readme.md                       # Este arquivo README
```
# Instale as bibliotecas
pip install pandas matplotlib seaborn plotly jupyter nbformat

## Passos para Execução

### 1 Clone o Repositório:
git clone [https://github.com/dfarneym/data_visualization](https://github.com/dfarneym/data_visualization)
cd DataVisualization

### 2 Abra o Notebook Jupyter:
````
jupyter notebook DataVisualization.ipynb

````
### 3 Execute as Células:
Dentro do navegador, o ambiente Jupyter será aberto. Execute as células do notebook sequencialmente. O notebook está estruturado para guiar você através das etapas de:

- Carregamento e Preparação dos Dados: Importação do conjunto de dados imigrantes_canada.csv e tratamento inicial.

- Análise Comparativa Brasil vs. Argentina: Criação e interpretação de gráficos de linha para comparar a imigração de ambos os países.

- Análise da Imigração da América do Sul: Visualização das tendências de imigração dos principais países sul-americanos.

- Visualizações Detalhadas e Customização: Geração de diversos tipos de gráficos (linha, boxplot, barras) utilizando Matplotlib e Seaborn, com customizações de tema e paletas de cores.

- Gráficos Interativos com Plotly: Criação de visualizações dinâmicas e salvamento em formato HTML.

## 📊 Visualizações e Insights Principais
O projeto explora e visualiza a imigração para o Canadá, focando em:

- Tendências Temporais: Gráficos de linha mostram a evolução do número de imigrantes ao longo dos anos para países como Brasil e Argentina, permitindo identificar picos e vales migratórios.

- Comparativos de Países: Análises que comparam o fluxo migratório de diferentes nações, como Brasil e Argentina, revelando que suas tendências eram semelhantes no início do período, mas com o tempo, a Argentina apresentou um aumento significativo entre 2000 e 2005, enquanto o Brasil teve seu maior aumento após 2005.

- Top Imigrantes: Gráficos de barras que destacam os 10 países com maior número total de imigrantes para o Canadá no período analisado. O Brasil é apresentado como o quarto país da América do Sul com mais imigrantes para o Canadá.

- Customização de Gráficos: Exemplos de como aplicar diferentes paletas de cores e remover elementos visuais desnecessários para melhorar a clareza e o impacto das visualizações.

- Gráficos Interativos: Utilização da biblioteca Plotly para criar gráficos dinâmicos que permitem ao usuário explorar os dados de forma mais aprofundada, salvando-os em um arquivo HTML para fácil compartilhamento.

## 💻 Tecnologias Utilizadas
- Python: Linguagem de programação principal.

- Pandas: Manipulação e análise de dados.

- Matplotlib: Criação de gráficos estáticos.

- Seaborn: Biblioteca para visualização estatística de dados, construída sobre o Matplotlib.

- Plotly: Criação de gráficos interativos e dinâmicos.

- Jupyter Notebook: Ambiente interativo para desenvolvimento e apresentação do código.

## Crie e ative um ambiente virtual (opcional, mas recomendado)
```
python -m venv venv
source venv/bin/activate  # No Linux/macOS
venv\Scripts\activate     # No Windows
```

