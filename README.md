# Trabalho_RedesNeurais

Código original disponível em https://github.com/ShunLu91/DU-DARTS

Dentro da pasta **DU-DARTS** a pasta **dataset** contém o dataset com as imagens utilizadas. Além disso, há também a pasta **log** que contém os modelos gerados e utilizados nos notebooks.

Para executar o código no colab basta subir a pasta **DU-DARTS** e alterar os caminhos de acordo com seu drive no próprio notebook.  

Os modelos gerados ao executar o _train_search_brain_ e o _retrain_brain_ vão para a pasta **log**. O arquivo do _train_search_ é o **weights.pt**, ele é utilizado no _retrain_ para treinar o modelo. O arquivo utilizado no _evaluate_brain_ é o **bests_weights.pt**, gerado após a execução do _retrain_. 
