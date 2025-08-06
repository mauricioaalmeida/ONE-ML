# ONE | TECH FOUNDATION - Especialização Data Science
Curso Estatística e Machine Learning G8 - ONE

# ETAPAS:
## Estatística

Na etapa de Estatística, você conhecerá os conceitos fundamentais que são essenciais para a análise de dados. Você aprenderá sobre estatística descritiva, como medidas de tendência central (média, mediana e moda) e dispersão (variância e desvio padrão). Esta etapa fornecerá a base matemática necessária para interpretar corretamente os dados e dar suporte à tomada de decisões confiantes.

- Curso Estatística com Python: resumindo e analisando dados

- Curso Estatística com Python: probabilidade e amostragem

## Regressão Linear

Nesta segunda etapa, você aprenderá a modelar dados utilizando regressão linear, começando pela visualização da distribuição dos dados para entender padrões. Será abordada a distinção entre variáveis dependentes e explicativas, além da separação dos dados em treinamento e teste. Você aplicará regressões usando ferramentas como Statsmodels e Scikit-learn, interpretará coeficientes estimados e utilizará métricas e resíduos para avaliar a qualidade dos modelos. Técnicas avançadas de modelagem e transformações nos dados serão exploradas para melhorar previsões, culminando na comparação dos melhores modelos e análise gráfica dos resultados obtidos.

 - Curso Data Science: testando relações com Regressão Linear
 - Curso Regressão Linear: técnicas avançadas de modelagem
 - Curso Classificação: aprendendo a classificar dados com Machine Learning

## Machine Learning: Compreendendo a base da classificação

Para começar, você aprenderá como diversos problemas do dia a dia podem ser resolvidos com o uso do aprendizado de máquina. Entenderá como o Machine Learning pode ser aplicado para melhorar processos e ajudar no crescimento de empresas e negócios, como, por exemplo, classificando clientes em categorias que podem indicar produtos ideais a serem oferecidos, otimizando assim as estratégias de vendas. E por fim, você realizará um projeto prático para prever atrasos de voos, colocando todos os conhecimentos adquiridos em prática.

- Curso Classificação: validação de modelos e métricas de avaliação
- Curso IA aumentada: prevendo atrasos de voos


# Exercícios:

## Estatística e Machine Learning G8 - ONE

Este repositório contém uma coleção de notebooks Jupyter desenvolvidos durante o curso de Estatística e Machine Learning do grupo G8 - Oracle Next Education. Os notebooks abordam desde conceitos básicos até projetos completos de análise de dados, classificação, regressão e redes neurais.

## Sumário dos Notebooks

### 1. Desafio_Diabetes.ipynb
- **Descrição:** Exercícios de classificação binária usando dados de diabetes. Abrange análise exploratória, criação de modelos com Decision Tree e Random Forest, avaliação de métricas, curvas ROC/PR e validação cruzada.
- **Exemplo de uso:** Predição de risco de diabetes com base em variáveis clínicas.

### 2. Desafios_Analise_Churn.ipynb
- **Descrição:** Análise de Churn de clientes de banco, com exploração de variáveis categóricas e numéricas, visualizações, e preparação para modelagem.
- **Exemplo de uso:** Exploração de dados para identificar padrões de evasão de clientes.

### 3. ONE_Classificacao_Marketing_Investimentos.ipynb
- **Descrição:** Projeto de classificação para prever a adesão de clientes a campanhas de investimento, com análise exploratória, tratamento de dados e construção de modelos de machine learning.
- **Exemplo de uso:** Prever se um cliente irá aderir a uma campanha de marketing.

### 4. ONE_Classificação_Validação_métricas.ipynb
- **Descrição:** Práticas de classificação, separação de dados em treino/validação/teste, avaliação de métricas (acurácia, precisão, recall, F1-score), matriz de confusão e curva ROC.
- **Exemplo de uso:** Avaliação de modelos de classificação para inadimplência em empréstimos.

### 5. Desafio_RL_Hoteis.ipynb
- **Descrição:** Análise de regressão linear para precificação de hotéis. Inclui análise de correlação, pairplot, construção e comparação de modelos, além de previsão de valores.
- **Exemplo de uso:** Estimar preços de quartos de hotel com base em características.

### 6. Desafio_RL_Energia.ipynb
- **Descrição:** Regressão linear aplicada a dados de uma usina de energia, com foco em multicolinearidade (VIF) e homocedasticidade (análise de resíduos).
- **Exemplo de uso:** Modelagem para prever produção de energia a partir de variáveis ambientais.

### 7. L2_Neural+Networks.ipynb
- **Descrição:** Exercício prático de redes neurais artificiais (ANN) em Python usando Keras/TensorFlow. Inclui geração de dados sintéticos, treinamento, avaliação, visualização de métricas e fronteira de decisão.
- **Exemplo de uso:** Classificação binária simples e visualização do processo de aprendizado de uma rede neural.

---

## Tecnologias Utilizadas

- **Python 3**
- **Jupyter Notebook**
- **Bibliotecas principais:**
  - pandas, numpy, matplotlib, seaborn, plotly
  - scikit-learn (modelagem, métricas, validação)
  - imblearn (balanceamento de classes)
  - statsmodels (regressão, VIF)
  - tensorflow/keras (redes neurais)

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/mauricioaalmeida/ONE-ML.git
   cd ONE-ML
   ```

2. Instale as dependências (recomenda-se usar um ambiente virtual):
   ```bash
   pip install -r requirements.txt
   ```
   > Caso não exista um arquivo `requirements.txt`, instale manualmente as principais bibliotecas citadas acima.

3. Execute os notebooks em sua máquina local ou via [Google Colab](https://colab.research.google.com/):
   - Basta abrir o notebook desejado e seguir as instruções em cada célula.

## Exemplos de Utilização

### Classificação de Diabetes
```python
import pandas as pd
from sklearn.tree import DecisionTreeClassifier

dados = pd.read_csv('data/diabetes.csv')
x = dados.drop('diabetes', axis=1)
y = dados['diabetes']

modelo = DecisionTreeClassifier()
modelo.fit(x, y)
pred = modelo.predict(x)
```

### Regressão Linear de Preço de Hotéis
```python
import pandas as pd
from sklearn.linear_model import LinearRegression

df = pd.read_csv('data/hoteis.csv')
X = df[['Estrelas', 'ProximidadeTurismo', 'Capacidade']]
y = df['Preco']

modelo = LinearRegression()
modelo.fit(X, y)
precos_preditos = modelo.predict(X)
```

## Contribuição

Novos desafios, melhorias e correções são bem-vindos! Abra uma issue ou pull request.

---

## Licença

Este projeto é livre para fins educacionais. Consulte o arquivo LICENSE para mais detalhes, se disponível.

---
