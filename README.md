# ONE-ML
Estatística e Machine Learning G8 - ONE


## Preço de casas

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

