<p align="center">
  <img src="assets/logo-pucpr-vermelha.png" height="80"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
</p>

<h1 align="center">🧠 neuro_vgg16</h1>

<p align="center">
  Classificação de Imagens Médicas com Deep Learning (VGG16 + ADAM)
</p>

<p align="center">

![Build Status](https://github.com/SEU_USUARIO/neuro_vgg16/actions/workflows/ci.yml/badge.svg)
![Python](https://img.shields.io/badge/python-3.10+-blue.svg)
![Framework](https://img.shields.io/badge/TensorFlow-Keras-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Colab](https://img.shields.io/badge/Run-Google%20Colab-yellow?logo=googlecolab)

</p>

---

## Objetivo  

Este projeto apresenta a implementação de um pipeline de **Deep Learning** voltado à classificação de imagens médicas, utilizando **Redes Neurais Convolucionais (CNNs)** com foco na arquitetura **VGG16**.

O objetivo é avaliar o desempenho do modelo em um cenário aplicado, utilizando dados reais obtidos via Kaggle e execução em ambiente **Google Colab**.

---

## Metodologia  

O experimento foi estruturado nas seguintes etapas:

- 📥 Aquisição dos dados via Kaggle  
- 🧹 Pré-processamento das imagens  
- 🔀 Divisão em conjuntos de treino e validação  
- 🧠 Aplicação de *Transfer Learning* com VGG16  
- ⚙️ Treinamento do modelo com otimizador ADAM  
- 📊 Avaliação de desempenho  

---

## Modelo Utilizado  

- Arquitetura: **VGG16**  
- Estratégia: *Transfer Learning*  
- Pesos iniciais: **ImageNet**  
- Ajustes: Camadas finais adaptadas para classificação de imagens médicas  

---

## Dataset  

- 📌 Fonte: Kaggle  
- 🧬 Tipo: Imagens médicas (Tomografia Computadorizada do cérebro)  
- 📦 Tamanho: ~66MB  

Dataset utilizado:  
Computed Tomography (CT) of the Brain  

🔗 https://www.kaggle.com/datasets/trainingdatapro/computed-tomography-ct-of-the-brain/code  

> ⚠️ O dataset não está incluído neste repositório.

---

### Reprodutibilidade  

Para garantir a reprodução dos experimentos, utilize a API do Kaggle:

1. Instale a dependência:
pip install kaggle
   
2. Configure sua credencial (`kaggle.json`)

3. Execute o download:

kaggle datasets download trainingdatapro/computed-tomography-ct-of-the-brain

4. Descompacte os dados:

unzip computed-tomography-ct-of-the-brain.zip

---

### Observação  

Este projeto foi estruturado para permitir a reprodução completa dos experimentos a partir da integração com o Kaggle, garantindo portabilidade e aderência às boas práticas de pesquisa.

---

## Como Executar  

### Executar no Google Colab  

👉 https://colab.research.google.com/drive/1YiCwUxZAKkfCcW1yBj_l1YpfAA7QTK4U  

---

### Passo a passo  

1. Baixar o dataset conforme seção anterior  
2. Garantir que os dados estejam no caminho correto  
3. Executar o notebook no Colab  

---

## Dependências  

- numpy  
- pandas  
- matplotlib  
- tensorflow / keras  
- scikit-learn  
- kaggle  

---

## Resultados  

O projeto contempla:

- 📊 Treinamento da rede VGG16  
- 📉 Evolução das métricas (*accuracy* e *loss*)  
- 🧪 Avaliação de desempenho do modelo  

---

## Observações  

- Projeto desenvolvido no **Google Colab**  
- Uso de **GPU** é recomendado para melhor desempenho  
- Dataset externo (não versionado no repositório)  

---

## 🏛️ Instituição  

**Pontifícia Universidade Católica do Paraná (PUCPR)**  
Programa de Pós-Graduação em Informática (PPGIA)  

---

## 👨‍💻 Autor  

**Gabriel Passos**  

Doutorando em Ciência da Computação pelo PPGIA/PUCPR. Mestre em Computação Aplicada pela UEPG. Pesquisa na interface Inteligência Artificial e Medicina. Tem atuação como Cientista de Dados. É professor universitário na área de Tecnologia da Informação, ministrando disciplinas nas áreas de Estruturas de Dados, Banco de Dados e Ciência de Dados. Orienta pesquisas de Iniciação Científica e TCC na área de Informática Médica.

---

## 📄 Licença  

Este projeto está licenciado sob a **Licença MIT**.  

Você pode utilizar, modificar e distribuir este código livremente, desde que os devidos créditos ao autor original sejam mantidos.
