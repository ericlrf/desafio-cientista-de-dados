# SELEÇÃO PÚBLICA SIMPLIFICADA DE TRANSFORMAÇÃO DIGITAL
___
## desafio-cientista-de-dados


### Entendimento do desafio
A regressão linear é uma ferramenta fundamental que tem vantagens sobre outros algoritmos de regressão

Devido à sua simplicidade, é um algoritmo excepcionalmente rápido para treinar, portanto, normalmente o torna um bom algoritmo para cenários de regressão comuns. É importante ressaltar que os modelos treinados com regressão linear são o tipo mais interpretável de modelos de regressão disponíveis: é mais fácil agir a partir dos resultados de um modelo de regressão linear. No entanto, se as premissas não forem satisfeitas, a interpretação dos resultados nem sempre será válida. Isso pode ser muito perigoso dependendo da aplicação.

### Diretrizes
A regressão linear é uma análise que avalia se uma ou mais variáveis preditoras
explicam a variável dependente (critério). A regressão tem cinco suposições principais:
1. Linear relationship;
2. Multivariate normality;
3. No or little multicollinearity;
4. No auto-correlation;
5. Homoscedasticity.

Usando os dados do Boston house prices dataset, que pode ser encontrado no python sklearn quando no R, execute:
1.  Estatística descritiva dos dados;
2.  Analise univariada considerando a distribuição de medidas e pico (Skewness e Kurtosis);
3.  Análise bivariada;
4.  Engenharia de Recursos;
5.  Respeitando as 5 suposições, gere o seu modelo de regressão.


### Diferencial
1. É possível afirmar que um modelo de regressão linear no conjunto de dados de Boston viola o número de suposições que causam problemas significativos com a
interpretação do próprio modelo? Explique.

### Dicionário de dados

Attribute Information (in order):
- CRIM   per capita crime rate by town.
- ZN   proportion of residential land zoned for lots over 25,000 sq.ft.;
- INDUS   proportion of non-retail business acres per town;
- CHAS  Charles River dummy variable (= 1 if tract bounds river; 0 otherwise);
- NOX  nitric oxides concentration (parts per 10 million);
- RM   average number of rooms per dwelling;
- AGE  proportion of owner-occupied units built prior to 1940;
- DIS  weighted distances to five Boston employment centres;
- RAD  index of accessibility to radial highways;
- TAX  full-value property-tax rate per $10,000;
- PTRATIO  pupil-teacher ratio by town;
- B  1000(Bk - 0.63)^2 where Bk is the proportion of black people by town;
- LSTAT  % lower status of the population;
- MEDV   Median value of owner-occupied homes in $1000's.
