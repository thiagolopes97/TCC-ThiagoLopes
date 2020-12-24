# Análise comparativa de modelos de machine learning na predição de câncer de pele


Trabalho de graduação para o curso de Engenharia Física da Escola de Engenharia de Lorena da USP. 
Tema: Análise comparativa de modelos de machine learning na predição de câncer de pele.

Este trabalho busca explorar modelos de aprendizado de máquina para classificação de câncer de pele através de características extraídas de imagens médicas. Esta análise contempla dois conjuntos de dados fornecidos por Mendonça et al. (2013) e Tschandl (2018), de domínio público, contendo uma série de imagens de lesões dermatológicas, máscaras de interesse e um arquivo com suas descrições. O primeiro contém 200 imagens divididas em 3 classes: nevo comum, nevo atípico e melanoma. Já o segundo, apresenta 10015 imagens divididas em 7 classes: lesões tipo ceratose benigna, dermatofibroma, nevos melanocíticos, lesões vasculares, carcinoma epidermoide, carcinoma basocelular e melanoma.

Utilizando conceitos médicos abordados sobre o assunto, grandezas quantitativas foram extraídas das imagens. Em seguida, utilizou-se destes atributos para o treinamento dos modelos, sperando os dados em treinamento e teste. Ademais, também foram otimizados alguns parâmetros computacionais de cada modelo no treinamento e buscou-se analisar a performance dos resultados de cada algoritmo para diferentes tratamentos de dados. Introduziu-se neste processo a Validação Cruzada, Padronização dos Dados e Synthetic Minority Oversampling Technique (SMOTE) para determinação dos melhores hiperparâmetros em cada caso e identificação de mudanças
significativas nos resultados gerados. Os dados extraídos e explorados aqui, foram obtidos por um módulo em Python (Extração de Dados).

Os modelos usados neste projeto são:

- Regressão Logística;
- Naive Bayes; 
- Árvore de Decisões; 
- Floresta Aleatória; 
- Árvores Extremamente Aleatória; 
- KNN (K-Nearest Neighbors); 
- RNN (Radiues Nearest Neighbors);
- Adaptative Boosting; 
- Gradient Boosting; 
- SVM (Support Vector Machine);
- Rede Neural Artificial Multi-layer Perceptron (RNA-MLP)

Diretórios:

Dentro das pastas HAM10000 e PH2, contém  pasta 'Datafeature' onde contém o script para extração das características das imagens e os valores destas salvas em arquivos .csv . Na pasta 'EDA' está um breve estudo dos dados usados no treinamento dos modelos, com a exploração gráfica e algumas correlações do mesmo com a classe. Na pasta 'BestParam' contêm o treinamento e avaliação de resultados dos modelos para o problema proposto. 

Referências:

- TSCHANDL, P. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Harvard Dataverse, 2018. Disponível em: <https://doi.org/10.7910/DVN/DBW86T>.
- MENDONÇA, T. et al. Ph2: A dermoscopic image database for research and benchmarking. International Conference of the IEEE Engineering in Medicine and Biology Society, v. 589, p. 1–15, 2013.  Disponível em: https://www.fc.up.pt/addi/ph2%20database.html.

----------------------------------------------------------------------------------------------------------------------------------------


English:

# Comparative analysis of machine learning models in skin cancer prediction


Graduation work for the Physical Engineering course at the Lorena Engineering School at USP.
Theme: Comparative analysis of machine learning models in skin cancer prediction.

This work seeks to explore machine learning models for the classification of skin cancer through features extracted from medical images. This analysis includes two sets of data provided by Mendonça et al. (2013) and Tschandl (2018), in the public domain, containing a series of images of dermatological lesions, masks of interest and a file with their descriptions. The first contains 200 images divided into 3 classes: common nevus, atypical nevus and melanoma. The second presents 10015 images divided into 7 classes: benign keratosis-like lesions, dermatofibroma, melanocytic nevi, vascular lesions, squamous cell carcinoma, basal cell carcinoma and melanoma.

Using medical concepts approached on the subject, quantitative quantities were extracted from the images. Then, these attributes were used for the training of the models, awaiting the data in training and testing. In addition, some computational parameters of each model in the training were also optimized and we sought to analyze the performance of the results of each algorithm for different data treatments. In this process, Cross Validation, Data Standardization and Synthetic Minority Oversampling Technique (SMOTE) were introduced to determine the best hyperparameters in each case and identify changes
significant results. The data extracted and explored here, were obtained by a module in Python (Data Extraction).

The models used in this project are:

- Logistic Regression;
- Naive Bayes;
- Decision Tree;
- Random Forest;
- Extremely Random Trees;
- KNN (K-Nearest Neighbors);
- RNN (Radiues Nearest Neighbors);
- Adaptive Boosting;
- Gradient Boosting;
- SVM (Support Vector Machine);
- Artificial Neural Network - Perceptron Multi-layer (ANN-MLP)

Directories:

Within the HAM10000 and PH2 folders, it contains a 'Datafeature' folder containing the script for extracting the characteristics of the images and their values saved in .csv files. In the folder 'EDA' there is a brief study of the data used in the training of the models, with the graphic exploration and some correlations of the same with the class. The 'BestParam' folder contains training and results evaluation of the models for the proposed problem.

References:

- TSCHANDL, P. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Harvard Dataverse, 2018. Available at: <https://doi.org/10.7910/DVN/DBW86T>.
- MENDONÇA, T. et al. Ph2: A dermoscopic image database for research and benchmarking. International Conference of the IEEE Engineering in Medicine and Biology Society, v. 589, p. 1–15, 2013. Available at: https://www.fc.up.pt/addi/ph2%20database.html.
