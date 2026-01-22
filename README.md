## **Este repositório contém análises do desafio Detecção de Perdas Não Técnicas**

No arquivo `application.ipynb`, é apresentada uma **Análise Exploratória de Dados (EDA)**, na qual são investigados padrões visuais e comportamentais associados a consumidores fraudulentos e não fraudulentos.

O notebook contempla uma etapa de **Engenharia de Atributos**, incluindo:
- Análise das variáveis originais do dataset;
- Criação de novas  features derivadas do histórico de consumo;
- Extração de atributos temporais capazes de capturar padrões de queda e comportamento  no consumo.

Na etapa de **Pré-Processamento** foram investigadas e aplicadas diferentes técnicas, tais como:
- Balanceamento de classes utilizando SMOTE, devido ao forte desbalanceamento entre classes;
- Transformação de atributos categóricos por meio de encoding;
- Normalização com Min-Max.

Foram aplicados algoritmos de classificação como:
- K-Nearest Neighbors (KNN)
- Random Forest

O modelo Random Forest foi adotado como principal devido à sua robustez e, sobretudo, à sua capacidade de interpretabilidade, possibilitando a análise da importância das variáveis no processo decisório.

Os modelos foram **Avaliados** por meio de validação cruzada estratificada, utilizando múltiplas métricas de desempenho, tais como:
- Acurácia
- Precisão
- Recall
- F1-score

Ao longo do notebook, são apresentadas discussões sobre:
- O comportamento dos modelos;
- A relevância das variáveis originais e das features criadas;
- As limitações do modelo e possibilidades de aprimoramento.



