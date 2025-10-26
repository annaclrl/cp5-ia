# 🎯 Modelo de Classificação para Diagnóstico de Câncer de Mama

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Concluído-success)

## 👨‍💻 Integrantes
- **Nome**: Anna Clara Russo Luca 
- **RM**: 561928
- **Turma**: 1TDSPW

## 📖 Sobre o Projeto

Este projeto desenvolve um modelo de Machine Learning para classificação binária de tumores de mama em **benignos** ou **malignos**, utilizando o dataset Breast Cancer Wisconsin. O objetivo é criar uma ferramenta de IA que auxilie profissionais de saúde no diagnóstico precoce do câncer de mama.

**🎯 Objetivo Principal**: Desenvolver um modelo preditivo preciso que possa servir como ferramenta de apoio ao diagnóstico médico, identificando padrões complexos nos dados que podem passar despercebidos ao olho humano.

## 📊 Dataset

### Fonte dos Dados
- **Nome**: Breast Cancer Wisconsin (Diagnostic) Dataset
- **Fonte**: [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

### Características do Dataset
- **Total de exames**: 569 pacientes
- **Variáveis**: 32 colunas por exame
- **Variável alvo**: `diagnosis` (B = Benigno, M = Maligno)
- **Distribuição**: 357 benignos (62.7%), 212 malignos (37.3%)

### Principais Características
As características computadas incluem:
- **Medidas de tendência central**: raio médio, textura média, perímetro médio, área média
- **Medidas de variação**: erro padrão das medidas
- **Medidas dos "piores" aspectos**: raio pior, textura pior, etc.
- **Características de forma**: suavidade, compactação, concavidade, pontos côncavos

## 🚀 Como Executar o Projeto

### Pré-requisitos
```bash
Python 3.8 ou superior
Jupyter Notebook ou Google Colab
```

### Execução no Google Colab 
- Acesse o Google Colab
- Faça upload do arquivo data.csv para a sessão
- Execute todas as células sequencialmente
