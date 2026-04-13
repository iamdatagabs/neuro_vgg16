# neuro_vgg16
Experimento de simulação de implementação do padrão arquitetural VGG16 com algoritmo ADAM em dataset de tomografia computadorizada (base do Kaggle)

# neuro_vgg16
Experimento de simulação de implementação do padrão arquitetural VGG16 com algoritmo ADAM em dataset de tomografia computadorizada (base do Kaggle)

# 🧠 Classificação de Imagens Médicas com VGG16

Este projeto implementa um pipeline de Deep Learning para classificação de imagens médicas utilizando a arquitetura VGG16, com dados obtidos via Kaggle e execução no Google Colab.

---

## 🚀 Objetivo

Desenvolver um modelo de classificação de imagens utilizando redes neurais convolucionais (CNN), com foco em aplicações na área médica/neuro, avaliando o desempenho da arquitetura VGG16 em um cenário real de dados.

---

## 🧠 Metodologia

O experimento segue o seguinte pipeline:

1. **Aquisição dos dados**
   - Download via API do Kaggle
   - Extração de arquivos compactados (ZIP)

2. **Pré-processamento**
   - Organização das imagens em diretórios
   - Ajuste de dimensões
   - Normalização dos dados

3. **Configuração experimental**
   - Definição de batch size
   - Número de épocas
   - Separação treino/validação (holdout)

4. **Modelagem**
   - Uso da arquitetura VGG16 (transfer learning)
   - Ajuste das camadas finais para classificação

5. **Treinamento**
   - Fine-tuning do modelo
   - Monitoramento de métricas

6. **Avaliação**
   - Análise de desempenho do modelo
   - Comparação de métricas

---

## 🤖 Modelo Utilizado

- **VGG16 (Transfer Learning)**
  - Base pré-treinada (ImageNet)
  - Camadas finais adaptadas para o problema

---

## 📈 Métricas de Avaliação

Dependendo da execução:

- Acurácia
- Loss (função de custo)
- Pode implementar precisão, recall e F1-score

---

## 📂 Estrutura do Projeto
├── notebooks/
│ └── Experimento1_VGG16.ipynb
├── data/ # (não incluído)
├── models/ # (opcional)
├── outputs/ # resultados e gráficos
└── README.md


---

## 📊 Dataset

- Fonte: Kaggle
- Tipo: Imagens médicas (neuro)
- Formato: arquivos compactados (.zip)

> ⚠️ Os dados não estão incluídos no repositório devido ao tamanho e políticas da plataforma.

---

## ▶️ Como Executar

### 🔹 Google Colab

Abra diretamente:

👉 https://colab.research.google.com/drive/1YiCwUxZAKkfCcW1yBj_l1YpfAA7QTK4U

---

### 🔹 Passos no Colab

1. Instalar Kaggle:
```bash
pip install kaggle

Fazer upload do kaggle.json
2. Baixar dataset:
kaggle datasets download ...

3. Descompactar:
unzip arquivo.zip

4. Executar todas as células

----
## 📄 Licença

Este projeto está licenciado sob a licença MIT.

Isso significa que você pode usar, modificar e distribuir este código livremente, desde que mantenha os créditos ao autor original.

Para mais detalhes, consulte o arquivo `LICENSE` neste repositório.

## 👨‍💻 Autor

Gabriel Passos  

- Professor de Engenharia e Tecnologia
- Doutorando em Ciência da Computação (PPGIa/PUCPR)  
- Mestre em Computação Aplicada (PPGCA/UEPG)
- Bacharel em Geograifia (UFV)
- Atuou em Ligas Acadêmicas vinculadas aos departamentos de Medicina e Enfermagem (DEM/UFV) e Nutrição e Saúde (DNS/UFV)
- Pesquisador em Machine Learning, Ciência e Engenharia de Dados, Bioinformática e Informática Médica  


📫 Contato: (adicione aqui se quiser — e-mail ou LinkedIn)
