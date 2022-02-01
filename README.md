# ADF_PIPELINE_MENTORIA_01
Pipeline desenvolvido dentro da mentoria de Engenharia de Dados

Detalhes do desafio:

1. Criar dois containers ADLS Gen2 chamados LANDING e RAW (não se preocupem com os nomes) que representarão nossa camada de recebimento dos dados brutos e armazenamento dos dados prontos para próximas fase respectivamente.
2. Fazer a ingestão do arquivo compactado direto do link disponibilizado para o container LANDING via Azure Data Factory.
4. Movimentar o arquivo da LANDING para RAW descompactando-o neste processo e armazenando de forma particionada (ANO, MES, DIA) pela data da carga.
