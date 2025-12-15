# 📊 Roteiro 6

## Conjunto de dados

`disponibilidade_internet.csv`

> Fonte: adaptado de https://www.kaggle.com/datasets/sudipde25/global-internet-adoption-trends?select=global_internet_adoption_monthly_2010_2025.csv

## Exercício 1

Carregue o conjunto de dados `disponibilidade_internet.csv` no Power BI e utilize o Power Query para realizar as seguintes operações de transformação de dados:

1. Remova as linhas em branco do conjunto de dados;
2. Corrija o cabeçalho da tabela, de forma que os nomes corretos das colunas sejam apresentados;
3. Remova as colunas que não contêm dados;
4. Divida a coluna `Pais_Zona` em duas colunas, a saber: `Pais` e `Zona`, de forma que a primeira contenha o nome do país e a segunda contenha a zona a que o registro se refere;
5. Remova as colunas `Latitude` e `Longitude`;
6. Junte as colunas `Ano`, `Mes` e `Dia` em uma única coluna, chamada `Data`, de forma que cada entrada dessa nova coluna contenha ano, mês e dia, separados por hífen (ex.: `2010-12-1`);
7. Altere o tipo de dado da coluna `Data` para data;
8. Crie uma nova coluna chamada `5G_sim_nao`, baseada no valor da coluna `5G_disponivel`, de forma que os valores da coluna `5G_sim_nao` sejam:
    - `Não`, se a coluna `5G_disponivel` contiver o valor `0`; ou
    - `Sim`, se a coluna `5G_disponivel` contiver o valor `1`.
9. Remova a coluna `5G_disponivel`;
10. Substitua os valores não disponíveis de uso de Internet móvel pelo valor `0`.
11. Verifique se todas as colunas estão utilizando os tipos de dados corretos e, se necessário, corrija-os.

## Exercício 2

Em seguida, construa um dashboard para extrair insights sobre a disponibilidade de Internet nos países relacionados. Durante o exercício, procure ter em mente que você está tentando responder à pergunta:

> Qual é a história que os dados contam?

Procure elaborar o seu dashboard para descrever o conjunto de dados da maneira mais detalhada possível, tentando levar em consideração todas as informações que podem ser extraídas dele e utilizando de maneira adequada os recursos de visualização que nós já estudamos.

