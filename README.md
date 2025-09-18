# Model Fitness 🏋️‍♂️

A Model Fitness é uma rede de academias dentre as mais reconhecidas do setor, oferecendo experiências personalizadas, equipamentos modernos e um ambiente confortável para seus clientes.

Apesar disso, a rotatividade de clientes (churn) ainda preocupa os gestores. Este projeto busca analisar os dados do último mês para identificar padrões de comportamento entre clientes que cancelam o serviço, destacando fatores como idade, tempo de uso e forma de contratação. O objetivo é prever o churn e apoiar estratégias para reduzir a evasão nos próximos meses.

## 📑 Índice

- 🔭 [Visão Geral](#visao-geral)
- 🔧 [Recursos](#recursos)
- 📊 [Análises Realizadas](#analises-realizadas)
- 🎯 [Conclusão Final](#conclusao-final)

---

<a id='visao-geral'></a>
## 🔭 Visão Geral

A Model Fitness, referência no setor de academias, enfrenta o desafio da rotatividade de clientes. Para lidar com esse problema, este projeto analisa dados do último mês com foco no Churn, buscando identificar padrões relacionados a idade, tempo de uso e forma de contratação. O objetivo é prever o comportamento de evasão e apoiar estratégias para retenção de clientes.

<a id='recursos'></a>
## 🔧 Recursos

- **Pandas** → limpeza, filtragem e manipulação de dados.
- **Seaborn** → visualização de correlação por meio de mapa de calor, histogramas e gráficos de distribuição.
- **Scikit-learn** → modelos de previsão, análise de métricas e agrupamento hierárquico por clusters.

<a id='analises-realizadas'></a>
## 📊 Análises Realizadas

O processo analítico realizado contemplou diferentes etapas para a exploração e compreensão dos dados. Inicialmente, foi feita a filtragem e preparação do dataset, garantindo a consistência das variáveis e a remoção de possíveis ruídos que pudessem comprometer as análises. Em seguida, aplicamos uma análise exploratória de dados (EDA), utilizando mapas de calor construídos com Seaborn para avaliar as correlações entre variáveis numéricas, de forma a identificar relações relevantes que pudessem influenciar no comportamento de churn. Complementarmente, foram gerados histogramas e gráficos de distribuição, também com Seaborn, para observar a dispersão das características e sua relação com o comportamento de permanência ou evasão dos clientes.

Além disso, foram desenvolvidos modelos de predição utilizando Regressão Logística e Floresta Aleatória, com o objetivo de avaliar a interpretabilidade dos dados e a capacidade de previsão da evasão de clientes. Para mensurar a confiabilidade dos modelos e do conjunto de dados, utilizamos métricas como acurácia, precisão e sensibilidade, permitindo uma visão mais robusta sobre a efetividade das abordagens e a qualidade das informações analisadas.

Para aprofundar a segmentação, aplicamos o algoritmo de K-Means, que permitiu a formação de clusters de clientes com perfis semelhantes. Essa abordagem possibilitou não apenas a identificação de padrões comuns em determinados grupos, mas também a detecção de perfis com maior propensão à saída do serviço nos próximos meses. A análise dos clusters auxilia, portanto, na definição de estratégias direcionadas de retenção, considerando o comportamento específico de cada segmento de clientes.

<a id='conclusao-final'></a>
## 🎯 Conclusão Final

A análise mostrou que a evasão é maior entre clientes que moram longe da academia, sugerindo a avaliação da abertura de novas unidades em locais estratégicos. Também identificamos que clientes jovens e com contratos curtos tendem a sair após o primeiro mês, sendo recomendado criar ofertas e incentivos para aumentar sua permanência. Por outro lado, clientes que utilizam serviços extras e atividades em grupo demonstraram maior fidelização, reforçando a importância dessas iniciativas para retenção.
