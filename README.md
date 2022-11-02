## Projeto Shark Attack

## Simple is better than complex.

Este repositório contém o estudo sobre a incidência de ataques de tubarões-tigre, em especifico no território dos USA onde se apresentou uma maior quantidade de casos para esta espécie.

## Bibliotecas utilizadas: Pandas e OS

## Fases do projeto:

1) Importaçao do DataSet -- > https://www.kaggle.com/datasets/teajay/global-shark-attacks?resource=download
2) Leitura inicial, identificaçao e remoção de colunas dispensáveis para a análise através do método Drop() --> ['pdf', 'href formula' 'href', 'Case Number.1', 'Case Number.2', 'original order', 'Unnamed: 22', 'Unnamed: 23']
3) Renomear os heads das colunas sensíveis para o estudo ['Case Number', 'Date', 'Year', 'Type', 'Country', 'Area', 'Location', 'Activity', 'Sex', 'Age', 'Injury', 'Fatal (Y/N)', 'Time', 'Species', 'Investigator or Source']
4) Remoção das linhas onde não constavam as espécies de nenhum tipo (Nan/empy values);
5) Criação de mascara para identificar apenas os ataques nos quais constavam a espécie Tiger;
6) Transformação da coluna 'Year' de float64 para int64
7) Descarte das incidências anteriores ao ano de 1543
8) Identificação do país ('Country') de maior quantidade de ataques reportados --> USA
9) Identificação da Area onde ocorreu a maior quantidade de ataques de tubarões-tigre no terrítório USA

#Conclusão: A área de maior incidência de ataques de tubarão-tigre é no Hawaii




