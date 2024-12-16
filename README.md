![logo ilum](https://github.com/pedrozanineli/aprendizado-de-maquina/blob/main/logo1.png)

## Aprendizado de Máquina
### Tema: Análise da expressão gênica da derme

**Membros e respectivos líderes de cada bloco**

- Artur Hosoi Kimura - 220048 - Bloco 2
- Débora van Putten Chaves - 220037 - Bloco 3
- Pedro Henrique Machado Zanineli - 220068 - Bloco  4
- Vitor Eduardo Girotto Barelli - 220072 - Bloco 1

Como forma de desenvolvimento da disciplina de Aprendizado de Máquina do segundo semestre do curso da Ilum Escola de Ciência, o projeto pretende identificar a idade e sexo de um determinado indivíduo ao analisar um conjunto de dados relacionados à expressão gênica na pele não exposta ao sol, retirados do BioBanco de dados "Portal GTEX".

**Informações importantes do projeto**

O projeto será desenvolvido considerando:
- Features expressas em TPM (transcrito por milhão) dos genes mais expressivos na pele segundi a literatura;
- Faixa etária como target, com subdivisões em faixas que exploram idades entre 20 aos 79 anos;
- Sexo como target, podendo ser classificado como masculino ou feminino.

## Sumário do repositório

***Geral***
- Diário de bordo.ipynb: são as anotações do líder do bloco (discussões, ações e a realização de tarefas)
- 'raw_data.zip': contém todos os nossos dados já tratados.

***Bloco 1***
- B1 - Coleta dos dados.ipynb: nesse caderno foram feitas coletas e tratamento de dois tipos de dados, produzindo um dataframe.
- B1 - Preparação e Análise dos dados.ipynb: nesse caderno houve uma discussão sobre o projeto em geral e a definição, classificação e preparação dos dados e features para serem analisadas.
- B1 - Dados.csv: Nesse arquivo Excel temos os dados retirados do GTX que serão utilizados para produzir os data.set
- B1 - material-de-estudo.md: reúne em um arquivo só os genes que encontramos destacados na literatura e os links para os artigos que continham tais informações.

***Bloco 2***
- B2 - Aplicação dos métodos com conversão randômica de idade.ipynb: Baseline, K-NN, Regressão Linear, Árvore de Decisão e Floresta Aleatória, por idades aleatórias.
- B2 - Aplicação dos métodos.ipynb: Baseline, K-NN, Regressão Linear, Árvore de Decisão e Floresta Aleatória, por faixa de idade.

OBS: Nesse bloco houve a separação do dataframe em 2;
- 'data.csv': pegamos todos os nossos genes e, a partir deles, somamos as suas expressões. Depois disso, analisamos quais deles eram mais expressivos (quais tinham as maiores somas) e selecionamos os 20 (vinte) que apresentaram maiores resultados.
- 'data_artigo.csv': os genes aqui escolhidos são os que foram obtidos da literatura científica. Os links para os artigos que suportam essas escolhas estão dispostos no arquivo 'material-de-estudo.md'.

***Bloco 3***
- B3 - Agrupamento (clustering).ipynb
- B3 - Detecção de valores anômalos.ipynb
- B3 - PCA.ipynb

***Bloco 4***
- B4 - Validação cruzada.ipynb

- ![ilum logo](https://github.com/pedrozanineli/aprendizado-de-maquina/blob/main/logo1.png)

## Machine Learning
### Topic: Analysis of Dermal Gene Expression

**Members and Their Assigned Blocks**

- Artur Hosoi Kimura - 220048 - Block 2  
- Débora van Putten Chaves - 220037 - Block 3  
- Pedro Henrique Machado Zanineli - 220068 - Block 4  
- Vitor Eduardo Girotto Barelli - 220072 - Block 1

As part of the Machine Learning course in the second semester at Ilum School of Science, this project aims to identify an individual's age and sex by analyzing a dataset related to gene expression in sun-unexposed skin, sourced from the “Portal GTEX” biobank.

**Important Project Information**

The project will consider:
- TPM (transcripts per million) features from the most expressive genes in skin tissue according to the literature;
- Age range as a target, subdivided into various groups spanning ages 20 to 79 years;
- Sex as a target, which can be classified as male or female.

## Repository Overview

***General***
- Diário de bordo.ipynb: Notes from the block leader (discussions, actions, and task execution).
- 'raw_data.zip': Contains all our preprocessed data.

***Block 1***
- B1 - Coleta dos dados.ipynb: Data collection and processing of two data types, producing a dataframe.
- B1 - Preparação e Análise dos dados.ipynb: General project discussion and the definition, classification, and preparation of data and features for analysis.
- B1 - Dados.csv: Excel file with the GTEX data that will be used to create our datasets.
- B1 - material-de-estudo.md: Consolidates the genes highlighted in the literature and provides links to the relevant articles.

***Block 2***
- B2 - Aplicação dos métodos com conversão randômica de idade.ipynb: Baseline, K-NN, Linear Regression, Decision Tree, and Random Forest, using random ages.
- B2 - Aplicação dos métodos.ipynb: Baseline, K-NN, Linear Regression, Decision Tree, and Random Forest, using age ranges.

**Note:** In this block, the dataframe was split into two:
- 'data.csv': We took all our genes, summed their expressions, analyzed which were most expressive (those with the highest sums), and selected the top 20.
- 'data_artigo.csv': The genes chosen here were obtained from the scientific literature. The links to the supporting articles are found in 'material-de-estudo.md'.

***Block 3***
- B3 - Agrupamento (clustering).ipynb  
- B3 - Detecção de valores anômalos.ipynb (Outlier detection)  
- B3 - PCA.ipynb (Principal Component Analysis)

***Block 4***
- B4 - Validação cruzada.ipynb (Cross-validation)

- ![ilum logo](https://github.com/pedrozanineli/aprendizado-de-maquina/blob/main/logo1.png)
