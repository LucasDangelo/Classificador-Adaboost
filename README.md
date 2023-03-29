# Classificador-Adaboost

Boosting é um método usado no machine learning para reduzir erros na análise preditiva de dados. Os cientistas de dados treinam softwares de machine learning, chamados modelos de machine learning, com dados rotulados para fazer suposições sobre dados não rotulados. Um único modelo de machine learning pode ter erros de previsão, dependendo da precisão do conjunto de dados de treinamento. Por exemplo, se um modelo de identificação de gato foi treinado apenas com imagens de gatos brancos, ele pode ocasionalmente identificar erroneamente um gato preto. O boosting tenta superar esse problema treinando vários modelos sequencialmente para melhorar a precisão geral do sistema.

Este caderno é uma cartilha introdutória  básica e simples para o método de ensemble (combinação) de modelos básicos de aprendizado, em particular a variante de ensemble conhecida como Stacking. 
Em suma, o empilhamento usa como primeiro nível (base) as previsões de alguns classificadores básicos e, em seguida, usa outro modelo no segundo nível para prever a saída das previsões anteriores do primeiro nível.
