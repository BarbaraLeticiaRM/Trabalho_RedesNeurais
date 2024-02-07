# Trabalho_RedesNeurais

Código original disponível em [DU-DARTS](https://github.com/ShunLu91/DU-DARTS)

As versões do Python e PyTorch utilizadas são, respectivamente, 3.7.10 e 1.7.1.

Dentro da pasta **DU-DARTS** a pasta **dataset** contém o dataset com as imagens utilizadas. Além disso, há também a pasta **log** que contém os modelos gerados e utilizados nos notebooks.

Para executar o código no colab basta subir a pasta **DU-DARTS** e alterar os caminhos de acordo com seu drive no próprio notebook.  

Os modelos gerados ao executar o _train_search_brain_ e o _retrain_brain_ vão para a pasta **log**. O arquivo do _train_search_ é o **weights.pt**, ele é utilizado no _retrain_ para treinar o modelo. O arquivo utilizado no _evaluate_brain_ é o **bests_weights.pt**, gerado após a execução do _retrain_. 

O código _mean_and_std_ serve apenas para calcular a média e o desvio padrão do dataset, para executá-lo basta alterar o caminho para o dataset. 
