# neuro_vgg16
Experimento de simulação de implementação do padrão arquitetural VGG16 com algoritmo ADAM em dataset de tomografia computadorizada (base do Kaggle)

🧠 Classificação de Imagens Médicas com VGG16

🚀 Objetivo

Este projeto implementa um pipeline de Deep Learning para classificação de imagens médicas utilizando redes neurais convolucionais (CNN), com foco na arquitetura VGG16.

O objetivo é avaliar o desempenho do modelo em um cenário real, com dados obtidos via Kaggle e execução no Google Colab.

🧠 Metodologia

O experimento segue as seguintes etapas:

Aquisição dos dados via Kaggle
Pré-processamento das imagens
Divisão em treino e validação
Aplicação de Transfer Learning com VGG16
Treinamento do modelo
Avaliação de desempenho
🤖 Modelo Utilizado
VGG16 (Transfer Learning)
Pesos pré-treinados (ImageNet)
Camadas finais adaptadas para classificação
📊 Dataset
Fonte: Kaggle
Tipo: Imagens médicas (neuro)
Formato: .zip

⚠️ Os dados não estão incluídos no repositório devido ao tamanho.

▶️ Como Executar
🔹 Abrir no Colab

Clique abaixo:

👉 https://colab.research.google.com/drive/1YiCwUxZAKkfCcW1yBj_l1YpfAA7QTK4U

🔹 Passos
Instalar dependências:
pip install kaggle
Fazer upload do kaggle.json
Baixar dataset:
kaggle datasets download ...
Descompactar:
unzip arquivo.zip
Executar o notebook
📦 Dependências
numpy
pandas
matplotlib
tensorflow / keras
scikit-learn
kaggle
📈 Resultados

O projeto apresenta:

Treinamento da rede VGG16
Evolução de acurácia e loss
Avaliação do desempenho do modelo


⚠️ Observações
Projeto desenvolvido no Google Colab
Uso de GPU recomendado
Dataset externo (não versionado no repositório)


👨‍💻 Autor

Gabriel Passos

Professor e pesquisador na área de Machine Learning, com foco em aplicações científicas, incluindo análise de dados e modelagem preditiva.

📄 Licença

Este projeto está licenciado sob a licença MIT.

Você pode usar, modificar e distribuir este código livremente, desde que mantenha os créditos ao autor original.
