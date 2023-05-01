# Classificador de AVCs

A metodologia utilizada para construir o classificador de AVCs foi a DecisionTreeClassifier, oferecida pelo scikit-learn. Ele classifica dados em conjuntos cada vez menores, formando uma árvore e sendo capaz de prever novos exemplos. Separamos um conjunto de dados de testes e um de treino, que não compartilhavam os mesmos dados, pois um servia para treinar o classificador e outro para realizar simulações do classificador. Por fim, calculamos a acurácia do modelo, através de testes de predição e uma função oferecida pelo próprio scikit-learn. O resultado encontrado foi de aproximadamente 94% de eficácia do programa, indicando que a princípio, ele teria alta previsão de acertos. No caso da hipótese nula, houve 96% de acurácia, indicando que existe, de fato, uma classe mais frequente no dataset (no caso, pessoas que não sofreram AVCs). Cruzando essas duas informações, podemos concluir que talvez o programa não tenha alta previsão de acertos apenas pelo seu treinamento, e sim pelo conjunto de dados também ter uma classe mais presente. Por fim, os 3 fatores com mais importância no modelo classificador foram gênero feminino, idosos e portadores de doenças cardíacas, o que pode ser embasado pela bibliografia a seguir, que são 3 artigos científicos sobre como esses 3 grupos de pessoas são mais propensos a terem AVCs. 

Bibliografia:

<a href=“https://pubmed.ncbi.nlm.nih.gov/20142445/“>Age-related differences in characteristics, performance measures, treatment trends, and outcomes in patients with ischemic stroke</a>

Heart Disease and Stroke Statistics—2021 Update | Circulation (ahajournals.org)

The Impact of Sex and Gender on Stroke - PMC (nih.gov)
