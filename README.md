# Portfólio

![https://j.pucsp.br/sites/default/files/ciencia-dados-1500px_vale_esta.jpg](https://j.pucsp.br/sites/default/files/ciencia-dados-1500px_vale_esta.jpg)

## Organização

- Introdução
- [Maratona Ciência de Dados](https://github.com/ludmilabueno/portfolio/tree/main/maratona-ciencia-de-dados)

## Introdução

Nesse repositório divulgo minha jornada de aprendizado em Ciência de Dados, nele coloco o que estou aprendendo e meus projetos.

## Maratona Ciência de Dados

Durante a maratona ciência de dados realizada no YouTube no canal [Victor Barros](https://www.youtube.com/channel/UCgQUqpzdiARaHpbADx7qUxQ) foi desenvolvido um projeto de Ciência de Dados. 

O projeto tinha o objetivo de dar uma visão geral da ciência de dados e deixar claro as etapas de um projeto. 

Esse projeto lidou com muitas bibliotecas amplamente utilizadas na ciência de dados, como o pandas, para a manipulação dos dados, matplotlib e seaborn, para a visualização dos dados e a scikit-learn, para machine learning.

Os dados utilizados no projeto são referentes as vendas feitas como resultado do marketing em diferentes meios de comunicação (TV, rádio e jornal).

O objetivo do projeto desenvolvido é avaliar como um meio de comunicação pode influenciar no resultado final das vendas. 

Para atingir o objetivo, primeiramente, foi necessário entender os dados e fazer uma análise. Então, utilizando a biblioteca pandas foi feita a importação do arquivo csv. 

Feito isso, foi feita a análise dos dados de forma concisa utilizando o método info() para descobrir se havia dados faltantes e os tipos de variáveis que se encontravam no DataFrame. 

Também foi utilizado o método describe() para visualizar informações de estatística descritiva dos dados, como média, desvio padrão, mediana, valor máximo e mínimo.

Entrando em visualização de dados, primeiramente foi utilizada a biblioteca matplotlib para construir boxplots para demonstrar a distrubuição referente a TV, Radio e Jornal. Depois, foi plotado os mesmos gráficos utilizando a biblioteca seaborn, para conseguir comparar as duas bibliotecas. É possível notar que a matplotlib é bem mais básica que a seaborn.

Outro gráfico plotado com seaborn foi o pairplot para demonstrar como as variáveis TV, jornal e rádio se relacionam com as vendas. Com isso, já é notável uma relação aproximadamente linear entre a TV e as vendas. 

Adentrando em machine learning, foi aplicada uma regressão linear com a biblioteca scikit-learn utilizando os dados da TV e de vendas. A partir disso, foi possível obter um modelo de predição, no qual é inserido o valor investido em marketing na TV e ele retorna uma previsão de vendas baseado nisso.etos.
