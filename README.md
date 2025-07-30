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

## 1.Preço de casas

Iremos estabelecer o preço de venda de casas, analisando as diversas características que influenciam sua precificação. 

### Vamos utilizar regressão linear como metodologia. 

### Utilizamos a base de dados [House Price](https://www.kaggle.com/code/ahmedmahmoud16/house-prices-regression) do Kaggle.
- Base preparada com algumas transformações: [Download](https://cdn3.gnarususercontent.com.br/3677-data-science-regressao-linear/Projeto/Base%20de%20dados/Pre%C3%A7os_de_casas.csv) 

- Campos disponíveis para análise:
   - area_primeiro_andar:
     - Refere-se à área do primeiro andar da propriedade, medida em metros quadrados.
   - existe_segundo_andar:
     - Esta variável é binária, indicando se a propriedade possui ou não um segundo andar. Pode ser representada como 1 para "sim" e 0 para "não".
   - area_segundo_andar:
     - Se a propriedade tiver um segundo andar, esta variável representa a área total do segundo andar, medida em metros quadrados.
   - quantidade_banheiros:
     - Número total de banheiros na propriedade.
   - capacidade_carros_garagem:
     - Capacidade da garagem da propriedade, ou seja, o número máximo de carros que podem ser estacionados na garagem.
   - qualidade_da_cozinha_Excelente:
     - Variável categórica que avalia a qualidade da cozinha na propriedade. Neste caso, assume-se que se a cozinha for considerada "Excelente" é representada por 1, e caso contrário, por 0.
   - preco_de_venda:
     - Preço de venda da propriedade em reais. É a variável alvo que se tenta prever usando os outros atributos da propriedade.
       
## 2.Hotéis

Análise do problema de precificação de quartos de hotéis usando Regressão Linear

[Notebook](https://github.com/mauricioaalmeida/ONE-ML/blob/main/Desafio_RL_Hoteis.ipynb)

## 3.Energia
Nesta atividade, vamos aplicar os conceitos de multicolinearidade e homocedasticidade em um contexto diferente: o setor de energia. Utilizaremos esse dataset de uma usina de energia para explorar como esses conceitos podem afetar os nossos modelos de regressão.
A tarefa envolve conduzir as seguintes etapas:

-Primeira etapa: Verifique a multicolinearidade utilizando o conceito de VIF. Se houver indícios de multicolinearidade entre as variáveis, tente pensar em quais medidas podem ser tomadas. Para isso você deverá construir um modelo de regressão linear assumindo que a coluna PE é a variável y.

-Segunda etapa: Realize uma análise de resíduos e identifique se há ou não heterocedasticidade nos dados.

[Notebook](https://github.com/mauricioaalmeida/ONE-ML/blob/main/Desafio_RL_Energia.ipynb)

## 4. Técnicas Avançadas - Imóveis no RJ
O mercado imobiliário vem sendo objeto de diversos estudos e pesquisas nos últimos tempos. A crise financeira que afeta a economia tem afetado significativamente os investimentos e ganhos advindos deste setor. Este cenário incentiva o aumento do interesse por estudos de previsão de demanda baseados em características deste mercado, dos imóveis e do entorno destes imóveis.

Neste contexto o objetivo principal do nosso projeto é desenvolver um sistema de avaliação imobiliária utilizando a metodologia de regressões lineares que é uma das técnicas de machine learning.

Nosso *dataset* é uma amostra aleatória de tamanho 5000 de imóveis disponíveis para venda no município do Rio de Janeiro.
Dados:

   - Valor - Valor (R$) de oferta do imóvel
   - Area - Área do imóvel em m²
   - Dist_Praia - Distância do imóvel até a praia (km) (em linha reta)
   - Dist_Farmacia - Distância do imóvel até a farmácia mais próxima (km) (em linha reta)

[Notebook](https://github.com/mauricioaalmeida/ONE-ML/blob/main/RL2_T%C3%A9cnicas_Avan%C3%A7adas.ipynb)
