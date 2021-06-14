## 💉&nbsp; Análise Vacinação Bahia

O Programa Nacional de Imunização foi criado em 18 de setembro de 1973 e é gerido atualmente pelo Ministério da Saúde e com a colaboração dos municípios. Esse programa se tornou uma referência mundial como um dos mais bem-sucedidos programas de imunização em massa. De acordo com o [site do Conass](https://www.conass.org.br/consensus/queda-da-imunizacao-brasil/) (Conselho Nacional de Secretários de Saúde), o Brasil foi pioneiro na incorporação de diversas vacinas no calendário do Sistema Único do Saúde (SUS) e é um dos poucos países no mundo que ofertam de maneira universal um rol extenso e abrangente de imunobiológicos. 

<br/>
<p align="center">
    <img width="80%" src="./imagens/vacinacao.jpg" alt="Vacinação">
</p>
<br/>

Graças a esse programa de vacinação em massa o Brasil conseguiu erradicar algumas doenças como a poliomelite, sarampo, rubéola, entre outras. 

## 🎲&nbsp; Origem dos Dados

Os dados que serão utilizados nesse projeto são disponibilizados pelo DataSUS através da sua plataforma de [Informações de Saúde (TABNET)](http://www2.datasus.gov.br/DATASUS/index.php?area=02). Primeiramente faremos uma análise como foi a cobertura de alguns imunos ao longo do tempo em todo território nacional, após isso a análise será mais restrita para o estado da Bahia.

## 💻&nbsp; Tecnologia

Versões utilizadas no projeto:

* <a href="https://www.python.org/downloads/release/python-388/">Python 3.8.8</a>
* <a href="https://pypi.org/project/notebook/6.3.0/">Jupyter Notebook 6.3.0</a>
* <a href="https://pandas.pydata.org/pandas-docs/stable/whatsnew/v1.2.4.html">Pandas 1.2.4</a>
* <a href="https://numpy.org/devdocs/release/1.20.1-notes.html">Numpy 1.20.1</a>
* <a href="https://matplotlib.org/3.3.4/users/installing.html">Matplotlib 3.3.4</a>
* <a href="https://seaborn.pydata.org/installing.html">Seaborn 0.11.1</a>

## 🤔&nbsp; Hipóteses 

* 1: O PNI está vacinando em maior ou menor quantidade nos últimos 4 anos?
* 2: É possível notar um decrescimento nos casos da vacina mais aplicada no Brasil pelo PNI?
* 3: As 3 vacinas mais aplicadas na Bahia também são as 3 mais aplicadas no Brasil?
* 4: É possível notar um decrescimento nos casos de poliomelite na Bahia?

## 📑&nbsp; Sumário

* <a href="./notebooks/01 - Coleta e Limpeza.ipynb">01 - Coleta e Limpeza</a>
* <a href="./notebooks/02 - Análise Exploratória - Cobertura Vacinal.ipynb">02 - Análise Exploratória - Cobertura Vacinal</a>
* <a href="./notebooks/03 - Análise Exploratória - Doses.ipynb">03 - Análise Exploratória - Doses</a>
* <a href="./notebooks/04 - Análisando Hipóteses.ipynb">04 - Análisando Hipóteses</a>

## ✅&nbsp; Conclusões

Através das análises feitas, pudemos observar que a média da Cobertura Vacinal caiu bastante, desde 2016 estamos com uma média de cobertura abaixo da média de todos os anos e o mesmo comportamento se repete com a quantidade de doses aplicadas. Com isso podemos afirma que nos últimos 4 anos o Brasil vem vacinando menos quando comparamos com todos os dados históricos.

Depois, descobrimos que a vacina mais aplicada no nosso país é a BCG, vacina que combate doenças como a meningite tuberculosa e a tuberculose miliar. Análisando os dados para tuberculose não foi possível perceber nenhum padrão, seja uma tendência ou sazonalidade. Caso tivesse algum padrão poderiamos ter tentado relacionar com a vacinação do BCG. Muito provavelmente, por falta de conhecimento da área de saúde, escolhi um procedimento errado para esse dataset e com isso pode ser que esses dados não tenham nada a ver com a tuberculose e a meningite combatida pelo BCG.

Posteriormente analisamos o ranking das vacinas aplicadas na Bahia em comparação com o Brasil e podemos afirmar que as 3 vacinas mais aplicadas na Bahia também são as três vacinas mais aplicadas no Brasil, mantendo a mesma ordem de colocação. Análisando os dados de poliomelite na Bahia não possível perceber nenhum padrão já que há poquíssimos casos de internações por poliomelite aguda. Talvez o ideal ao analisar esse tipo de doença seja olhar para os dados de produção ambulatorial, onde pode ser que os casos que ainda existem de poliomelite não conseguem se agravar ao ponto de exigir uma internação. O mesmo comportamento se repete para a esfera nacional, onde ao longo dos anos tivemos poucos casos de internações de poliomelite aguda. Somente em janeiro de 2008 que no Brasil houve um pico chegando a 9 internações.


## 📘&nbsp; Contato

<p>
<a href="https://www.linkedin.com/in/icaro-carneiro" target="_blank"><img alt="LinkedIn - Ícaro Carneiro" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

<br/>
<p align="center">
    <img width="40%" src="./imagens/sus.png" alt="Defenda o SUS">
</p>
<br/>