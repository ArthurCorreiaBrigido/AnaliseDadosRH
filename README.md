# AnaliseDadosRH

## Descrição
Este projeto apresenta uma análise exploratória aplicada a um conjunto de dados fictícios de Recursos Humanos e visa responder perguntas de negócio que contribuem para melhor compreensão do perfil dos funcionários, experiência profissional em anos, fatores relacionados a níveis de satisfação no trabalho e influências em decisões de promoção.

## Perguntas a serem respondidas
1 - Qual o total de funcionários atualmente na empresa?

2 - Qual o tempo médio de experiência dos funcionários (em anos)?

3 - Qual o total e percentual de funcionários do gênero masculino e feminino?

4 - Qual a média salarial mensal?

5 - Qual o total de funcionários por função?

6 - Qual o percentual de funcionários disponíveis para fazer hora extra?

7 - Qual o nível de envolvimento dos funcionários no trabalho considerando 4 categorias: Ruim, Baixo, Médio e Alto?

8 - Qual o total e o percentual de funcionários que devem receber promoção? Considere a coluna “Anos Desde a última Promoção” com a seguinte regra: Se o funcionário tiver 5 anos ou mais desde a última promoção, deve ter a promoção considerada. Caso contrário, a promoção não deve ser considerada agora.

## Estrutura do Projeto
1. Carregamento, leitura e tratamento dos dados
  - Conjunto de dados `DadosRH.csv` é carregado usando a biblioteca `pandas`.
  - Inspeção das colunas e tipos de dados
  - Verificação de duplicatas, valores nulos e ausentes
  - Padronização de variáveis categóricas

2. Análise Exploratória Univariada
  - **Idade**
    - A distribuição mostrou diversidade etária, indicando equipe variada entre profissionais jovens e experientes.
  - **Variáveis categóricas (Gênero, Estado Civil, Departamento, Função, Viagem, Disponibilidade de horas extra, Envolvimento e Status para Promoção.)**
    - Frequências apresentadas em gráficos de barras, mostrando a distribuição dos funcionários em cada grupo.
  - **Distribuição da Satisfação no trabalho**
    - Permitiu identificar tendências gerais de satisfação, possibilitando uma avaliação do clima organizacional e taxa de rotatividade.

3. Respostas das perguntas de negócio
  - Todas as perguntas foram respondidas utilizando funções da biblioteca `pandas` para cálculos.

## Requisitos
- Python 3.x
- Bibliotecas:
  - pandas
  - matplotlib
  - seaborn 
