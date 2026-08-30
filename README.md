# ResNet-50 em Tiny ImageNet

Implementação e treinamento de uma **ResNet-50** em PyTorch para classificação de imagens no **Tiny ImageNet**, seguindo a arquitetura apresentada no paper [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385).

O dataset utilizado possui 200 classes e 100.000 imagens de treinamento. Para este experimento, foram utilizadas 30.000 imagens para treinamento e 10.000 para validação, com imagens redimensionadas para 224×224 pixels. O dataset está disponível no [Kaggle](https://www.kaggle.com/datasets/akash2sharma/tiny-imagenet).

O treinamento foi realizado por 30 épocas em uma GPU Tesla T4, utilizando SGD com momentum e Cosine Annealing.