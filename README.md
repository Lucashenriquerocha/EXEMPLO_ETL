##Objetivo
O objetivo do projeto é realizar análises de vendas de duas filiais de uma empresa, com a extração de dados de arquivos CSV e Excel, realizando devidas transformações e armazenando em arquivos CSV e em um banco de dados SQLite. Além disso, foram feitas consultas SQL para obter os dados armazenados no banco de dados.

##Arquivos e Dados
analise_vendas.py é responsável por realizar todas as etapas do projeto, a extraçã, transformação dos dados, o armazenamento e consulta no banco de dados. Foi utilizado a biblioteca Pandas para a manipulação dos dados e a biblioteca sqlite3 para a interação com o banco de dados SQLite.

##Arquivos de Dados:
vendas_filial1.csv são os dados de vendas da Filial 1.
vendas_filial2.xlsx são os dados de vendas da Filial 2.
##Transformações de Dados
Para cada filial, foi calculado o valor total das vendas, multiplicando a quantidade vendida pelo preço unitário de cada produto.
> Os dados transformados foram visualizados no console e posteriormente salvos em arquivos CSV.
> Os dados transformados também foram carregados para um banco de dados SQLite.
Arquivos Gerados
vendas_filial1_transformadas.csv e vendas_filial2_transformadas.csv contém os dados transformados de cada filial.
dados_transformados.db contém as tabelas vendas_filial1_transformadas e vendas_filial2_transformadas.

##Consultas SQL
Foram realizadas consultas SQL para obter os dados armazenados no banco de dados.
As consultas retornaram os mesmos dados transformados que foram visualizados anteriormente no console.

##Conclusão
Este projeto demonstra um fluxo básico de análise de dados, desde a extração e transformação até o armazenamento e consulta em um banco de dados. A utilização de bibliotecas como Pandas e sqlite3 facilita o processo de manipulação e análise de dados, enquanto o uso de arquivos CSV e bancos de dados oferece opções para armazenamento e consulta eficientes dos dados.

![image](https://github.com/Lucashenriquerocha/EXEMPLO_ETL/assets/112584046/d48a0777-6f32-4846-92c3-20cd6141f473)
![image](https://github.com/Lucashenriquerocha/EXEMPLO_ETL/assets/112584046/09fb1160-bbde-4c48-be1c-c673501d0df6)
![image](https://github.com/Lucashenriquerocha/EXEMPLO_ETL/assets/112584046/b163398a-d8e3-4d22-aedf-311cf087ba20)
![image](https://github.com/Lucashenriquerocha/EXEMPLO_ETL/assets/112584046/584a7dde-4a12-4d88-85f9-539b209f256b)

