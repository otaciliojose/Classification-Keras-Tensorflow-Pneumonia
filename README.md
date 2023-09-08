# Classification-Keras-Tensorflow-Pneumonia

# Projeto de Classificação Binária de Raio-X para Detecção de Pneumonia
### Objetivo:
Desenvolver um modelo de Deep Learning utilizando a biblioteca Keras para classificação binária de imagens de raio-x em dois grupos: pneumonia e normais.

### Subobjetivos:
- Pré-processamento dos Dados: Carregar e normalizar as imagens de raio-x. Dividir o conjunto de dados em treinamento e teste. Aplicar técnicas de aumento de dados para aumentar a variabilidade do conjunto de treinamento.

- Seleção e Treinamento de Modelos Pré-treinados: Utilizar arquiteturas de modelos pré-treinados como VGG16, InceptionV3, ResNet... Realizar transfer learning para adaptar esses modelos ao problema específico.

- Adição de Camadas Densas: Adicionar camadas densas para a classificação binária no topo dos modelos pré-treinados. Utilizar funções de ativação apropriadas.

- Implementação de Técnicas de Normalização: Testar tipos diferentes de normalização: formato de pixels (dividir todos os valores dos pixels por 255), Z-score, aumento de contraste usando transformação gama, Group Normalization, Layer Normalization e Batch Normalization avaliando o impacto na performance do modelo.

- Ajuste de Hiperparâmetros e Otimização: Realizar experimentos para otimização de hiperparâmetros, como taxa de aprendizado, tamanho do lote, etc.

### Resumo:
O projeto visa desenvolver um sistema de classificação binária de imagens de raio-x para detecção de pneumonia. Isso é alcançado através da utilização de modelos pré-treinados e técnicas de normalização, como Batch Normalization, Layer Normalization e Group Normalization... O conjunto de dados é pré-processado, dividido em conjuntos de treinamento e teste, e técnicas de aumento de dados são aplicadas. Diferentes arquiteturas pré-treinadas são testadas e ajustadas através de transfer learning, e camadas densas são adicionadas para a tarefa de classificação.
