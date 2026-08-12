# Classificação Binária


## Descrição do Problema


O objetivo deste projeto é o treinamento de uma rede neural artificial para a identificação e classificação de classes binárias. Para este estudo, foi utilizado o dataset Raisin Binary Classification, que consiste em um conjunto de dados com características morfológicas de duas variedades de uvas passas: Kecimen e Besni. O banco de dados original apresenta um bom equilíbrio natural entre a contagem de ambas as classes, garantindo uma divisão justa para o treinamento.


## Tecnologias Utilizadas 


Projeto desenvolvido em linguagem Python utilizando o ambiente Google Colab e Jupyter Lab. Para a manipulação de dados, utilizou-se as bibliotecas pandas e numpy; para o pré-processamento e as métricas, scikit-learn; para a construção e o treinamento da rede neural, utilizou-se tensorflow; para a visualização de dados, matplotlib e seaborn.


## Como Executar


Certifique-se de ter o Python propriamente instalado na sua máquina e as bibliotecas citadas acima. Depois, baixe o dataset do Kaggle ou utilize o arquivo Raisin_Dataset (1).csv. É importante que o arquivo do dataset esteja no mesmo diretório que o arqivo ipynb. Após isso, considerando que já se tenha o Jupyter Notebook instalado no seu computador, execute o arquivo ipynb célula por célula ou todas de uma vez.



## Resultados 


Com as configurações encontradas no arquivo .ipynb, a partir da matriz de confusão, foi possível criar uma rede neural que obteve sucesso ao identificar as classes nos casos verdadeiros positivos e verdadeiros negativos. Os casos falsos positivos e falsos negativos foram considerados minoria. Constatou-se também que, como de costume, o desempenho nos dados de treinamento originais se mostrou superior àquele visto nos dados reais. 

