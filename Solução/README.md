# Solução do CASE

Este repositório contém a solução do CASE com três notebooks Jupyter organizados para tratar, explorar e treinar um modelo de classificação para os dados fornecidos.

## Estrutura do Repositório

- `Tratamento dos Dados.ipynb`
- `Analise exploratoria.ipynb`
- `Treinamento.ipynb`

### 1. Tratamento dos Dados.ipynb

Neste notebook, realizamos o carregamento inicial e o pré-processamento dos dados. As principais etapas incluem:

- **Carregamento dos Dados**: Importação dos dados brutos para análise.
- **Pré-processamento**: Limpeza dos dados, remoção de valores ausentes e tratamento de inconsistências.
- **Remoção de Características**: Identificação e remoção de colunas irrelevantes para a análise.
- **Tratamento de Datas**: Conversão de colunas de datas para o formato adequado e extração de informações úteis (ex. ano, mês).
- **Tratamento de Dados Categóricos**: Codificação de variáveis categóricas usando técnicas apropriadas (ex. One-Hot Encoding).

### 2. Analise exploratoria.ipynb

Este notebook é dedicado à análise exploratória dos dados, onde examinamos a distribuição e as estatísticas das variáveis. As principais etapas incluem:

- **Visualização da Distribuição dos Tipos de Pagadores**: Gráficos e estatísticas descritivas para entender melhor os diferentes tipos de pagadores.
- **Estatísticas de Faixa de Valores**: Análise das faixas de valores para diversas variáveis e identificação de tendências.
- **Remoção de Outliers**: Identificação e remoção de outliers para melhorar a qualidade dos dados e a performance dos modelos de classificação.

### 3. Treinamento.ipynb

No último notebook, focamos no balanceamento dos dados, na seleção e treinamento do modelo de classificação. As principais etapas incluem:

- **Balanceamento dos Dados**: Técnicas de oversampling/undersampling para equilibrar as classes no conjunto de dados.
- **Teste de Modelos de Classificação**: Avaliação de diferentes algoritmos de classificação para encontrar o mais adequado.
- **Treinamento do Melhor Modelo**: Treinamento do modelo selecionado com os melhores parâmetros encontrados.
- **Análise dos Resultados**: Avaliação da performance do modelo através de métricas como matriz de confusão, precisão, recall e f1-score. Visualização dos resultados e análise de erros (falsos positivos e falsos negativos).

## Outros Detalhes

1. **Clone o repositório**: git clone git@github.com:MatheusDiogo/challenge-data-scientist.git
2. **Versão Python**: 3.9.13
3. **Bibliotecas Utilizadas**: pandas, matplotlib, sklearn, seaborn, numpy, mlxtend