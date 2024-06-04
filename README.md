# Otimizacao de Hiperparametros

## Parâmetros e Hiperparâmetros
<b>Parâmetros</b>: Ajuste diretamente no aprendizado. Através de um conjunto de parâmetros o algoritmo encontra uma função que minimiza as perdas em um conjunto de dados, isto é, são intrínsecos à equação do modelo.

Exemplos: Coeficientes de uma regressão linear, pesos em uma rede neural artificial, variáveis em árvores de decisão...

<b>Hiperparâmetros</b>: argumentos ajustáveis que permitem controlar o processo de aprendizagem. Definidos anteriormente ao treinamento. 
Não são aprendidos diretamente pelo algoritmo de aprendizado.
Previne problemas de overfitting e underfitting.
Controla a capacidade do modelo.

Exemplos:  profundidade de uma árvore, número de árvores, taxa de aprendizagem, número de camadas e número de neurônios, função kernel...

## Otimização ou Ajuste de Hiperparâmetros
Indica a configuração de hiperparâmetros que resulta no melhor desempenho do algoritmo.

As configurações ideais de hiperparâmetros geralmente diferem para diferentes conjuntos de dados, portanto, devem ser otimizados para cada conjunto de dados.

Podem ser discretos (número de camadas) ou contínuos (intervalo entre um mínimo e máximo).

## Métodos comuns de otimização de Hiperparâmetros
1 - Manualmente.

2 - Grid Search (testa todas as combinações possíveis de todos os valores definidos anteriormente).

3 - Random Search (testa aleatoriamente as combinações de faixas de valores em uma quantidade de vezes definida pelo usuário).

4 - Otimização Bayesiana (algoritmo aprende com os testes anteriores e testa faixas de valores com base na probabilidade de melhores resultados dos hiperparâmetros).

## Métodos de otimização de Hiperparâmetros
O ajuste consiste em procurar por:

1 - Seleção dos hiperparâmetros principais.

2 - Definição de um espaço de hiperparâmetros.

3 - Aplicação da validação cruzada.

4 - Utilização de uma métrica de desempenho para validação.







