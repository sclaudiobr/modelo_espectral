# modelo_espectral

Mineração de dados espectrais com bibliotecas Scikit Learn e computação na nuvem 

Claudio R. O. da Silva¹

Este relatório apresenta um método para elaborar modelos de predição comparando o desempenho entre os algoritmos KNN, Adaboost, Árvore de Decisão e Random Forest, implementados  na linguagem de programação python através da plataforma de computação de código aberto Collaboratory e bibliotecas de aquisição, processamento e apresentação. Os métodos foram aplicados sobre um conjunto de dados de reflectância mensurado de classes de cobertura e uso do solo: solo exposto, solo úmido, grama, vegetação arbustiva, brita e asfalto, os quais foram amostrados com o sensor “FieldSpec HandHeld II", os dados obtidos com o instrumento cobre o intervalo espectral de 300 nm a 1.3 micron em varredura contínua com resolução espectral de 1 nm ASD (2010).  A segmentação dos espectros se deu pelo fatiamento nos intervalos equivalentes aos comprimentos de ondas na região do espectro nos intervalos do visível (0,43-0,68m) e do infravermelho próximo (0,85-0,88m) discretizadas nas classes denominadas VIS e NIR, respectivamente. Os indices de desempenho foram estimados através de métrcas da acurácia entre os algoritmos e apresentadas por meio de uma matriz de confusão.
