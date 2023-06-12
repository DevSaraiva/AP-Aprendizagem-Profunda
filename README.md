# Aprendizagem-Profunda
## Sistema de Deteção e Classificação de Máscaras Faciais


Devido ao seu tamanho, o modelo final poderá ser tranferido na [DropBox](https://www.dropbox.com/s/9f0d83rmuxnnrw3/CNNModel-final25.pth?dl=0) ou, caso não seja possível, no [WeTransfer](https://we.tl/t-h1LvZAP1SI) (indisponível ao fim de 7 dias)


O presente projeto conta com:

- **[face-mask-detection-pytorch.ipynb](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/blob/main/face-mask-detection-pytorch-allLabels.ipynb)** Ficheiro com todo o processo relativo ao modelo desenvolvido, desde obtenção de dados, tratamento, visualização, análise e definição do modelo.
- **[testSetMaker](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/tree/main/testSetMaker)** Funcionalidades relativas ao conjunto de dados utilizados para teste 
  - **[face-mask-detection-classsifier-using-cnn.ipynb](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/blob/main/testSetMaker/face-mask-detection-classsifier-using-cnn.ipynb)** Ficheiro correspondente ao modelo obtido através do Kaggle para comparação com o modelo desenvolvido
- **[maskIncorrectDataMaker](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/tree/main/maskIncorrectDataMaker)** Ficheiro para produzir um conjunto de imagens com a máscara colocada incorretamente
- **[faceDataMaker](https://github.com/DevSaraiva/AP-Aprendizagem-Profunda/tree/main/faceDataMaker)** Funcionalidades para obter um conjunto de imagens sem máscara
