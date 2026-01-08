# Projeto-Pima-Indians-Diabetes
O objetivo deste trabalho é comparar o desempenho do classificador Support Vector Machine (SVM) em dois esquemas de validação cruzada

# Resumo
O estudo utiliza o conjunto de dados Pima Indians Diabetes, amplamente conhecido em pesquisas sobre predição de diabetes, contendo atributos biomédicos como glicose, pressão arterial, IMC, espessura da pele e idade. O objetivo principal é avaliar o impacto da estratégia de validação cruzada no desempenho do modelo SVM, comparando: KFold-10 (validação cruzada padrão) RepeatedStratifiedKFold (10×3)Repetindo o processo 3 vezes e preservando o balanceamento das classes Além disso, o código inclui: Tratamento de valores ausentes (zeros transformados em NaN) Imputação com média Padronização dos atributos (StandardScaler) Busca de melhores hiperparâmetros com GridSearchCV Comparação por acurácia, desvio padrão e matrizes de confusão
