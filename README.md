O projeto busca comprovar a relação (ou a ausência de relação) entre os sintomas de depressão e algumas variáveis como: idade, etnia, gênero e prática de exercícios físicos.

## **DADOS** 
Os dados foram extraídos da pesquisa NHNES (*National Health and Nutrition Examination Survey*) realizada anualmente nos EUA para avaliar a saúde e nutrição de adultos e crianças.

O projeto utiliza dados referentes ao período de 2005 a 2006.

Foram utilizadas duas bases de dados que foram unificadas logo no início do projeto:

- **DEMO_PHQ.csv** \
Dados demográficos e resultados do  *Patient Health Questionnaire-9*  (PHQ-9), usado para avaliar o grau de sintomas depressivos.

- **PAG_HEI.csv** \
Dados referentes à atividade física.

Os dicionários das bases estão anexados ao projeto.

## **ESTRUTURA**
O projeto foi dividido da seguinte maneira:

- **LEITURA DO BANCO E TRATAMENTO DOS DADOS** \
Os dados são lidos dos arquivos .csv e carregados em DataFrames. Depois, para facilitar as análises, as respostas dos participantes em relação aos sintomas depressivos são agrupadas.

- **ANÁLISE EXPLORATÓRIA UNIVARIADA** \
Algumas variáveis são analisadas isoladamente resultando em novos ajustes nos dados. Esses ajustes são importantes para facilitar as análises futuras ou corrigir problemas que poderiam contaminar o resultado.

- **ANÁLISE EXPLORATÓRIA BIVARIADA** \
Nesse ponto são exibidos alguns gráficos que tentam evidenciar a relação entre duas variáveis.
Essa etapa é importante para sugerir hipóteses que serão verificadas no próximo tópico.

- **TESTES DE HIPÓTESES** \
Aplicação de testes estatísticos para aceitar ou rejeitar as hipóteses que foram levantadas.
