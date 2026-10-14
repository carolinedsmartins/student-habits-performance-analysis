# Análise de Hábitos de Estudo e Desempenho Acadêmico

## Sobre o projeto

Este projeto tem como objetivo explorar a relação entre hábitos de estudo, estilo de vida e desempenho acadêmico, utilizando Python para realizar uma análise exploratória de dados.

Foram analisadas variáveis como horas de estudo, uso de redes sociais, saúde mental, prática de exercícios físicos, qualidade da alimentação, gênero e notas dos exames.

## Ferramentas utilizadas

- **Python:** linguagem utilizada na análise.
- **Pandas:** leitura, manipulação e análise dos dados.
- **Matplotlib:** criação de visualizações.
- **Seaborn:** construção de gráficos estatísticos.

## Análises realizadas

### 1. Correlação entre as variáveis

Foi utilizado um mapa de calor (*heatmap*) para analisar a correlação entre as variáveis selecionadas.

A correlação entre horas de estudo por dia e nota do exame foi de **0,83**, indicando uma forte associação positiva. Já a avaliação de saúde mental apresentou correlação de **0,32** com as notas, indicando uma associação positiva moderada.

### 2. Horas de estudo e desempenho

Um gráfico de dispersão com linha de tendência foi utilizado para investigar a relação entre o tempo dedicado aos estudos e as notas dos exames. A visualização indicou uma tendência positiva entre essas variáveis.

Também foram comparadas as médias de desempenho de dois grupos:

- **Mais de 5 horas de estudo por dia:** média de 90,79 pontos.
- **Menos de 2 horas de estudo por dia:** média de 45,56 pontos.

Os resultados mostram uma diferença expressiva entre as médias dos grupos analisados.

### 3. Uso de redes sociais

O tempo diário dedicado às redes sociais foi explorado para compreender os padrões de utilização dos estudantes.

Os dados foram agrupados em três faixas de tempo — de 0 a 2 horas, de 2 a 4 horas e de 4 a 6 horas — e comparados por meio de um gráfico boxplot, permitindo observar a distribuição das notas em cada grupo.

### 4. Hábitos saudáveis

Foram analisadas as variáveis relacionadas à frequência de exercícios físicos, à avaliação de saúde mental e à qualidade da alimentação.

As visualizações sugeriram associações entre hábitos saudáveis e desempenho acadêmico, especialmente em relação à prática de exercícios físicos e à avaliação de saúde mental.

### 5. Análise por gênero

Foram calculadas a média e o desvio padrão das notas dos exames por gênero. As médias foram próximas entre os grupos Female (69,74) e Male (69,37).

O grupo Other apresentou média de 70,65, porém possui apenas 42 observações, enquanto Female possui 481 e Male, 477. Por isso, o resultado desse grupo deve ser interpretado com cautela, não sendo possível concluir que exista uma diferença relevante de desempenho entre os grupos.

## Principais conclusões

- As horas de estudo apresentaram forte correlação positiva com as notas dos exames (0,83).
- Estudantes que estudavam mais de 5 horas por dia obtiveram média de 90,79 pontos, enquanto aqueles que estudavam menos de 2 horas apresentaram média de 45,56 pontos.
- A avaliação de saúde mental apresentou correlação positiva moderada com as notas (0,32).
- A análise também explorou possíveis associações entre desempenho, uso de redes sociais e hábitos saudáveis.
- As médias das notas foram semelhantes entre Female e Male. O resultado de Other deve ser interpretado com cautela devido ao menor número de observações.

## Aprendizados

O projeto permitiu praticar a manipulação de dados com Pandas, a análise de correlações, o agrupamento de variáveis, o cálculo de estatísticas descritivas e a criação de visualizações com Matplotlib e Seaborn.

Além da parte técnica, a análise contribuiu para desenvolver a interpretação dos resultados e a comunicação de conclusões com base em dados.

## Limitações

A análise é exploratória e identifica associações entre variáveis, sem demonstrar relações de causa e efeito. As conclusões também dependem das características da base de dados utilizada.

## Como executar o projeto

1. Baixe ou clone este repositório.
2. Instale as bibliotecas necessárias: `pandas`, `matplotlib` e `seaborn`.
3. Mantenha o arquivo `student_habits_performance.csv` na mesma pasta do notebook.
4. Abra o notebook no Visual Studio Code ou Jupyter Notebook e execute as células.

**Arquivo de dados:** `student_habits_performance.csv`.