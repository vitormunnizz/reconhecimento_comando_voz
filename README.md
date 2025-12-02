Aqui está o README.md no modelo solicitado:

---

# Reconhecimento de Comando de Voz com Suavização

## Descrição do Projeto

Este projeto tem como objetivo desenvolver um sistema de **Reconhecimento de Comando de Voz** utilizando técnicas de suavização de sinais. A suavização aplicada ajuda a melhorar a qualidade do áudio e o desempenho do reconhecimento, reduzindo ruídos e variações abruptas. A partir de amostras de áudio, o sistema extrai características, como **MFCCs** (Mel-Frequency Cepstral Coefficients), e utiliza classificadores de machine learning para identificar corretamente os comandos de voz.

## Funcionalidades

- **Pré-processamento de Áudio**: Limpeza e filtragem de ruídos no sinal de áudio.
- **Suavização de Sinais**: Aplicação de técnicas de suavização para melhorar a qualidade do reconhecimento.
- **Extração de Características**: Extração de **MFCCs** e outras features relevantes para representar os comandos de voz.
- **Treinamento e Avaliação de Modelos**: Treinamento de modelos de machine learning para classificação de comandos com base nas features extraídas.
- **Validação e Métricas de Desempenho**: Avaliação do modelo por meio de métricas como **Acurácia**, **Precisão**, **Recall** e **F1 Score**.

## Requisitos

Para executar este projeto, são necessárias as seguintes dependências:

- `Python 3.x`
- `librosa`
- `numpy`
- `matplotlib`
- `scipy`
- `scikit-learn`
- `jupyter`

## Descrição da Base de Dados

O projeto utiliza uma base de dados de áudio contendo amostras de comandos de voz. As principais características da base de dados incluem:

- **Áudio**: Amostras de comandos de voz pré-processadas (10 arquivos de áudio representando o comando "ligar", 10 arquivos de áudio representando o comando "fechar", 10 arquivos de áudio representando o comando "abrir").
- **Classes de Comando**: Cada amostra de áudio é rotulada com o comando correspondente.
- **Extração de Features**: Para cada áudio, são extraídas features como **MFCCs**.

A base de dados é dividida em conjuntos de treino e teste, e é utilizada para treinar e avaliar os modelos de machine learning.

## Resultados

Os resultados do projeto mostram uma melhora significativa no desempenho do reconhecimento de voz ao utilizar técnicas de suavização. A acurácia e outras métricas de desempenho (como **F1 Score**) indicam que o modelo é capaz de distinguir comandos de voz com precisão, mesmo em condições de ruído.

### Principais Métricas:

- **Acurácia**: Percentual de predições corretas.
- **Precisão**: Percentual de verdadeiros positivos em relação a todas as predições positivas.
- **Recall**: Percentual de verdadeiros positivos em relação a todos os positivos reais.
- **F1 Score**: Média harmônica entre precisão e recall.

## Contato

Se você tiver dúvidas ou sugestões, entre em contato por [vitor13muniz09@gmail.com](mailto:vitor13muniz09@gmail.com).
