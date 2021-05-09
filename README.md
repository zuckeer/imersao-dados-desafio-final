
# Desafio Final Imersão Dados - 3ª edição

Um convite irrecusável para aqueles interessados no estudo das ciência de dados, a Imersão foi uma grata surpresa e uma jornada gratificante.  
Desenvolvida entre os dias 3 e 7 de maio de 2021, a jornada foi dividida em aulas diárias, seguindo o cronograma abaixo:  
03/05 - Aula 01: Análise de dados, python, pandas e genética  
04/05 - Aula 02: Estatísticas, visualização de dados e distribuições  
05/05 - Aula 03: Correlações, causalidade e relações entre genes  
06/05 - Aula 04: Merge de dados e análise de resultados  
07/05 -  Aula 05: Machine Learning, Sci-kit Learning e desafios envolvidos  

Além das aulas e do material de apoio fornecido pela [Alura](https://www.alura.com.br) contamos ainda com o suporte indispensável dos membros do Scuba Team e da ajuda dos participantes da imersão através de um server do [Discord](https://discord.com).  
  
Distribuídos em salas, o trabalho de descoberta e aprendizado foi catalisado pela energia desse grupo impressionante de pessoas.  
  
Não poderíamos deixar de agradecer ao auxílio generoso da [Vanessa Leiko](https://www.linkedin.com/in/vanessa-leiko-oikawa-cardoso/), do [Thiago G.Santos](https://twitter.com/tgcsantos), do [Guilherme Silveira](https://twitter.com/guilhermecaelum) e do [Paulo Silveira](https://www.linkedin.com/in/paulosilveira/). Nossa gratidão pela dedicação e pela oportunidade.  

Se mais extensões, vamos aos dados do Projeto.  

## Projeto  
  
O projeto apresentado utilizou os dados dosponibilizados através da competição [Mechanisms of Action (MoA) Prediction - Can you improve the algorithm that classifies drugs based on their biological activity?](https://www.kaggle.com/c/lish-moa/overview), disponível no Kaggle em https://www.kaggle.com/c/lish-moa/overview.  
  
Segue a transcrição original do desafio:  
  
_In this competition, you will have access to a unique dataset that combines gene expression and cell viability data. The data is based on a new technology that measures simultaneously (within the same samples) human cells’ responses to drugs in a pool of 100 different cell types (thus solving the problem of identifying ex-ante, which cell types are better suited for a given drug). In addition, you will have access to MoA annotations for more than 5,000 drugs in this dataset._  

## Bibliotecas utilizadas  
  
Foram utilizadas as bases fornecidas pela Alura de dados dos experimentos e a base dos resultados das análises. 
 
- [Pandas](https://pandas.pydata.org/docs/user_guide/index.html#user-guide);
- [Numpy](https://numpy.org/learn/)
- [Scikit learn](https://scikit-learn.org/stable)
- [Seaborn](https://seaborn.pydata.org)
- [Matplotlib](https://matplotlib.org)
  
## Modelos de Machine Learning
  
Foram usados ao longos dos testes com os dados os seguintes modelos de ML:
- [LogisticRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html?highlight=logisticregression#sklearn.linear_model.LogisticRegression)
- [DummyClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.dummy.DummyClassifier.html?highlight=dummyclassifier#sklearn.dummy.DummyClassifier)
- [DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html?highlight=decisiontreeclassifier#sklearn.tree.DecisionTreeClassifier)
- [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html?highlight=randomforestclassifier#sklearn.ensemble.RandomForestClassifier)  
