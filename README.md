# Diabetes Pima Data Science Project

Este projeto explora o **dataset Pima Indian Diabetes** através de uma abordagem de ciência de dados. O objetivo é aplicar diferentes técnicas de pré-processamento, treinamento de modelos e análise de desempenho para compreender os dados e construir modelos preditivos robustos.

## Estrutura do Projeto

O projeto está organizado em um notebook contendo exercícios, onde são aplicados os seguintes passos:

### 1. Análise Exploratória e Métricas Iniciais
- **Distribuição das Classes:** Calcular a porcentagem de presença de cada classe no dataset.
- **Acurácia do Modelo Ingênuo:** Avaliar um modelo base que sempre prevê a classe majoritária.

### 2. Treinamento de Modelos Simples
- **Modelo Perceptron Simples:** 
  - Estrutura de entradas e uma camada de saída com função de ativação logística.
  - Gráfico da função de custo em relação ao número de épocas para os conjuntos de treinamento e validação.
  - Acurácia do modelo no conjunto de teste (divisão 70% treinamento / 30% teste).
  - Matriz de confusão com análise das dificuldades por classe.
  - Exemplos de erros cometidos pelo modelo.

### 3. Rede Multilayer Perceptron (MLP)
- **Treinamento de MLP:** 
  - Avaliação de diferentes arquiteturas.
  - Busca de hiperparâmetros, incluindo número de épocas e número de neurônios por camada.
  - Seleção da melhor arquitetura.
- **Análise do Modelo MLP:**
  - Repetição das etapas de análise do modelo Perceptron Simples.

### 4. Pré-Processamento dos Dados
- **Imputação de Dados:**
  - Repetir as etapas descritas acima após lidar com valores ausentes no dataset.
- **Imputação e Normalização:**
  - Implementar a normalização em um pipeline.
- **Imputação, Normalização e PCA:**
  - Aplicar PCA como parte do pipeline de normalização.

### 5. Comparação de Resultados
- **Comparação Final:**
  - Comparar os resultados obtidos nos diferentes cenários de pré-processamento e modelos.
  - Discutir os impactos das técnicas utilizadas na performance do modelo.

## Requisitos do Projeto

### Tecnologias Utilizadas
- **Linguagem:** Python
- **Bibliotecas:** 
  - Pandas, NumPy (Manipulação de Dados)
  - Matplotlib, Seaborn (Visualização)
  - Scikit-learn (Pré-processamento, Modelos e Métricas)
  - TensorFlow ou PyTorch (Modelagem Neural)

### Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/ciaograsso06/diabetes-pimas-data-science.git
   cd diabetes-pima-data-science
