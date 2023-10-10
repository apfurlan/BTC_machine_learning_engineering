# BTC_machine_learning_engineering

Colunas - características - dimensões

Linhas - Instancias


1 - Principais algoritmos : 

- Regrassao logística
- Árvore de decisão
- Naive Bayes
- Support Vector Machines
- KNN

2 - Multiclasses : Quanto tenho mais que 
duas classes de sáida possíveis.

Exemploe é o caso do problema da Iris. Existem 3 espécies possíveis como saída,
reconhecimento facial é outro exemplo de Multiclasses. 


Os algoritmos mais usados são Regressão logística e SVM. Foram 
desenvolvidos para classificação binária. Existem ainda : 
 - Random Forest
 - Gradient Boosting
 - Redes Neurais Artificias. 


3 - Multi-Labels : quando um entrada (linha) pode pertencer
a mais de uma classe. Os algoritmos mais utilizados são : 
     - Multi-label Árvore de Decisão
     - Multi-label Random Forest
     - Multi-label Gradient Boosting
no entanto ainda existe a necessidade de realizar algumas 
adaptações. 

4 - Desbalanceada : quando a distribuição de instancias 
em cada classe de saída (label) não está balanceada. Nestes 
casos é bom usar algumas estratégias de amostragem para tentar 
balancear o dataset. Alguns exemplos são : 
    - Random Undersampling - reduzo a maior para balancear
    - SMOTE Oversampling - gero outras amostrar com as mesmas caracteristas
    da classe que tem menos, balanceando a amostra. 

    Estratégias de avaliação : Precision, Recall, F1-score, Matriz de Confusão e
    curva ROC. 

## Agrupamento


