# PROJETO_INDIVIDUAL_4

## Descrição do Projeto
Este relatório tem o objetivo de demonstrar a importância da análise dos dados de um projeto de desenvolvimento de software ao longo de uma semana.

Os dados fornecidos permitirão ao proprietário da equipe de desenvolvimento obter insights sobre o progresso do projeto, identificar possíveis áreas de melhoria e tomar decisões informadas para
garantir o sucesso do projeto.

Este projeto utiliza a linguagem de programação Python e a biblioteca pandas uma das bibliotecas mais populares para realizar a análise dos dados. 

A análise é feita em cima de um conjunto de dados que contém informações sobre as atividades realizadas em cada dia da semana durante a semana de desenvolvimento.

## Métricas Calculadas:
1. Total de horas trabalhadas: Calcula a soma das horas trabalhadas em todos os dias da semana.
2. Média diária de horas trabalhadas: Calcula a média das horas trabalhadas em cada dia da semana.
3. Total de bugs corrigidos: Calcula a soma dos bugs corrigidos em todos os dias da semana.
4. Média diária de bugs corrigidos: Calcula a média dos bugs corrigidos em cada dia da semana.
5. Total de tarefas concluídas: Calcula a soma das tarefas concluídas em todos os dias da semana.
6. Média diária de tarefas concluídas: Calcula a média das tarefas concluídas em cada dia da semana.
7. Produtividade diária (Tarefas Concluídas por Hora): Calcula a produtividade diária dividindo o número de tarefas concluídas pelo número de horas trabalhadas em cada dia.

## Como Executar o Código
Para executar o código e realizar a análise dos dados, siga os passos abaixo:

1. Certifique-se de ter o Python instalado em seu sistema.
2. Instale as bibliotecas necessárias: pandas e matplotlib. Isso pode ser feito através do pip ou de um ambiente de desenvolvimento Python como o Anaconda.
3. Copie o código fornecido neste repositório para um ambiente Python, como o Jupyter Notebook ou o Google Colab.
4. Execute o código linha a linha para obter as métricas e visualizações dos dados.

## Funcionamento do Código
O código está dividido em diferentes partes, cada uma com uma tarefa específica:

## Importação de bibliotecas: 
Inicialmente, a biblioteca pandas é importada para manipular os dados em forma de DataFrame.

## Carregamento dos Dados: 
Os dados sobre as atividades de desenvolvimento são fornecidos em um dicionário. Esse dicionário é transformado em um DataFrame usando a função pd.DataFrame() do pandas.

## Dicionário de Variáveis
### Estrutura do dicionário 'dados'

`dados`: Um dicionário contendo informações sobre as atividades realizadas em cada dia da semana.
* `Dias`: Lista com os nomes dos dias da semana (segunda a domingo).
* `Horas` Trabalhadas': Lista com o número de horas trabalhadas em cada dia.
* `Bugs Corrigidos`: Lista com a quantidade de bugs corrigidos em cada dia.
* `Tarefas Concluídas`: Lista com o número de tarefas concluídas em cada dia.

`DataFrame`: Um DataFrame criado usando a biblioteca pandas a partir do dicionário "dados", contendo os seguintes campos:
* `Dias`: Dias da semana.
* `Horas Trabalhadas`: Total de horas trabalhadas em cada dia.
* `Bugs Corrigidos`: Total de bugs corrigidos em cada dia.
* `Tarefas Concluídas`: Total de tarefas concluídas em cada dia.
* `Produtividade Diária`: Média diária de tarefas concluídas por hora trabalhada em cada dia.

`total_horas_trabalhadas`: Armazena o total de horas trabalhadas em toda a semana.

`media_diaria_horas_trabalhadas`: Armazena a média diária de horas trabalhadas com duas casas decimais.

`total_bugs_corrigidos`: Armazena o total de bugs corrigidos em toda a semana.

`media_diaria_bugs_corrigidos`: Armazena a média diária de bugs corrigidos com duas casas decimais.

`total_tarefas_concluidas`: Armazena o total de tarefas concluídas em toda a semana.

`media_diaria_tarefas_concluidas`: Armazena a média diária de tarefas concluídas com duas casas decimais.

`produtividade_diaria`: Uma série que representa a produtividade diária (tarefas concluídas por hora trabalhada) para cada dia.

## Resultados das análise
### Horas Trabalhadas
- A média de horas trabalhadas durante a semana é de: **6.43 horas**.
- A quarta tem a maior quantidade de horas trabalhadas: **8 horas**.
- O sábado tem a menor quantidade com: **5 horas**.
  
![image](https://github.com/JaymersonFerreira/PROJETO_INDIVIDUAL_4/assets/68979342/1fe8a805-53a1-49f5-9558-6688fe393fed)

### Bug corrigidos

- O total de bugs corrigidos por semana é: **16 bugs**
- A média de bugs corrigidos é de **2.43**.
- A quinta tem a maior quantidade de bugs com: **4 bugs**
- A quarta tem a menor quantidade de bugs com: **1 bug.** **negrito**

![image](https://github.com/JaymersonFerreira/PROJETO_INDIVIDUAL_4/assets/68979342/22cd785e-3245-4515-b7e5-80072f0201ab)

### Tarefas concluídas
- O total de tarefas comcluídas é de: **29 tarefas**
- A média de tarefas concluídas é de: **4.14 tarefas**.**negrito**
- A quarta tendo a maior quantidade de tarefas comcluidas com: **6 tarefas**.
- O domingo tem a menor qunatidade de tarefas concluidas com: **2 tarefas**.

![image](https://github.com/JaymersonFerreira/PROJETO_INDIVIDUAL_4/assets/68979342/c592ce4b-5223-41f5-8141-19edc719d288)

### Produtividade Diária
- A média de produtividade diária ao longo da semana é de: **0.64 tarefas por hora**.
- A segunda tendo a maior produtividade diário com: **0.83 tarefas por hora**.
- O domingo tem a menor produtividade diária com: **0.33 tarefas por hora**.
- A variação da Produtividade Diária é de: **0.50 tarefas por hora**.

![image](https://github.com/JaymersonFerreira/PROJETO_INDIVIDUAL_4/assets/68979342/866f8acf-af77-4442-b368-dc3b2592e424)

### Análise comparativa
- A produtividade e as tarefas concluídas parece ter uma relação, quando a produtivida é alta o números de tarefas entregues também é alta.
- A produtividade está mais relacionada com a conclusão de tarefas, do que com a correção de bugs específicos.
- Na quarta a produtividade tarefas concluídasão é altas, e o número de bugs corrigidos é baixo. Isso pode sugerir que a equipe está focando mais em concluir tarefas do que em corrigir bugs nesses dias.
- A quarta e o sábado são os dias com as menores produtividades e o menores números de tarefas concluídas.

![image](https://github.com/JaymersonFerreira/PROJETO_INDIVIDUAL_4/assets/68979342/ef0e115f-273e-4738-ba01-c432e5efbe7b)


## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou reportar problemas caso encontre algum bug ou tenha sugestões para melhorias.

## Desenvolvedores 
Jaymerson Ferreira

## Licença
Não há licença.

## Status do projeto
Finalizado
