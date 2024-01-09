# Análise de Séries Temporais na Região Sudeste: Explorando a Correlação entre Consumo de Energia Elétrica e Temperatura 2019 - 2020


## Introdução:

O conjunto de exercícios aborda a análise da correlação entre o consumo de energia elétrica e a temperatura na região sudeste do Brasil. Os dados foram fornecidos em dois conjuntos, um relacionado ao consumo de energia e outro à temperatura. O objetivo é explorar a relação entre essas variáveis ao longo do tempo.



## Metodologia:

Granularidade da Base de Dados:

Energia: A granularidade abrange o período de janeiro de 2004 a dezembro de 2020, com resolução mínima mensal.

Temperatura: A granularidade compreende de 15 de julho de 2018 a 31 de dezembro de 2020, com resolução diária.

Processamento do Dataframe Energia:

1. Atribuição da coluna temporal como índice.
2. Seleção de dados entre 2019 e 2020.


Processamento do Dataframe Temperatura:

1. Atribuição da coluna temporal como índice.
2. Seleção de dados entre 2019 e 2020.
3. Remoção de linhas com valores nulos.
4. Combinação das três colunas de temperatura em uma única coluna, calculando a média.
5. Reamostragem para a granularidade dos dados de consumo de energia, usando a média como métrica de agregação.

## Ferramentas Utilizadas:

Linguagem de Programação: Python
Bibliotecas: Pandas, Seaborn, NumPy

## Conclusão:

A análise de correlação entre o consumo de energia elétrica residencial e a temperatura média da região sudeste revelou uma correlação positiva. Isso sugere que, em geral, o consumo residencial aumenta com o aumento da temperatura. No entanto, para o consumo comercial, a pandemia impactou significativamente, resultando em uma diminuição no consumo durante parte de 2020. O consumo industrial, por sua vez, não demonstrou uma correlação clara com a temperatura, indicando que outros fatores podem influenciar esse setor. Essas conclusões são baseadas em análises visuais e cálculos de coeficiente de Pearson.
