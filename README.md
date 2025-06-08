# Previsão de Atrasos em Entregas Logísticas

Este projeto utiliza ciência de dados aplicada à logística de entregas de uma empresa de e-commerce. Através da análise estatística e de algoritmos de Machine Learning, buscamos prever se um pedido será entregue dentro do prazo ou não.

## Objetivo
Identificar os principais fatores que influenciam os atrasos nas entregas e construir modelos preditivos para apoiar decisões logísticas.

## Técnicas Utilizadas
- Análise Descritiva
- Visualização de Dados (Seaborn, Matplotlib)
- Modelagem com:
  - Regressão Logística
  - Árvore de Decisão
  - Random Forest

## Resultados
- Melhor modelo: Random Forest
- Acurácia: 66%
- AUC: 0.74
- Principais variáveis preditoras:
  - Desconto aplicado
  - Peso do produto
  - Número de chamadas ao SAC

## Base de Dados
Extraída do Kaggle (https://www.kaggle.com/datasets/prachi13/customer-analytics), contém 11.000 registros com variáveis sobre envio, produto, cliente e status da entrega.

## Recomendações
- Monitorar o impacto de grandes descontos.
- Criar estratégias para produtos mais pesados.
- Integrar o modelo ao sistema para alertar atrasos em tempo real.

## Autor
Marlon Patrick Magest Filgueiras  
Estudante de Ciência de Dados e Business Intelligence  
Universidade Católica de Petrópolis
