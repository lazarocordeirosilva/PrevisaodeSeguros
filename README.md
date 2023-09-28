![healthinsurance](https://github.com/lazarocordeirosilva/PrevisaodeSeguros/assets/132832478/ffca5ae5-b468-4236-9017-db62c86aae2b)

# *Previsão de Cobrança de Seguros*
O presente projeto apresenta uma base de dados contendo informações acerca de planos de saúde. Este trabalho tem sua utilidade decorrente do fato de que, para consolidar sua lucratividade, é necessário que uma seguradora de saúde arrecade mais prêmios do que gasta com seus segurados. Nesse sentido, há uma demanda pela construção de modelos de Machine Learning com capacidade de realizar predições acuradas acerca dos gastos médicos que cada beneficiário pode apresentar. Neste trabalho foram utilizados modelos cuja proposta reside na resolução de um problema de regressão. 

A base de dados utilizada é apresentada no livro "Machine Learning with R" de Brett Lantz, disponível [aqui](https://github.com/stedy/Machine-Learning-with-R-datasets).

## *Objetivo*
O objetivo deste projeto é construir um modelo de Machine Learning que seja capaz de resolver o problema de regressão relacionado à previsão dos gastos de saúde que um segurado pode apresentar, tendo como base suas características.

## *Requisitos* 
Neste projeto, foi utilizada a versão 3.11.4 do Python

A versão do pip utilizada é a 23.2.1

A versão do git utilizada é a 2.42.0

Demais requisitos se encontram no arquivo requirements.txt

## Replicação 
> [!IMPORTANT]
> Para utilizar este projeto, é necessário clonar o repositório 

```
git clone https://github.com/lazarocordeirosilva/PrevisaodeSeguros.git
```
> [!IMPORTANT]
> Após isso, você pode instalar os pacotes nas versões utilizadas
```
pip install -r requirements.txt
```

## Processamento
No desenvolvimento do projeto foi feito:
* EDA
* Codificação de Variáveis
* Feature Scaling
* Técnicas de Cross-Validation para competição de modelos
* Análise de significância estatística
* Previsão por meio de inputs


## Estrutura do Projeto 

├── LICENSE
├── README.md               <- README.md com principais informações do projeto.
├── data
│   ├── data dictionary     <- Dicionário dos dados utilizados no projeto.
│   └── raw                 <- Base de dados bruta (original).
├── notebooks               <- Jupyter notebook contendo toda a manipulação de dados e modelagem.
├── requisitos              <- Todas as bibiliotecas utilizadas (em cada versão). Arquivo gerado com 'pip freeze > requirements.txt'





