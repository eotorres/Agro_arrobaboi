# Analises Agro 

Utilizado a coletagem de dados, para validar as variações dos valores da @ (FUNRURAL), valores a vista, entre estados, datas

# Intuito do projeto e bibliotecas

Utilizado as seguintes bibliotecas :
  * requests
  * bs4 import BeautifulSoup
  * pandas as pd
  * numpy as np
  * import csv
  * import os
  * from os import listdir
  * from os.path import isfile, join

O projeto consiste em realizar a coleta de dados nos seguintes sites :
  *  Valores do boi gordo : 'https://www.scotconsultoria.com.br/cotacoes/boi-gordo/'
  *  Valores CEPEA        : 'https://www.cepea.esalq.usp.br/br/indicador/boi-gordo.aspx'
  *  Valores Pregão       : 'http://www2.bmf.com.br/pages/portal/bmfbovespa/lumis/lum-ajustes-do-pregao-ptBR.asp'


O estudo consiste em validar varias fontes e logo apos a validação unir em uma unica base para os devidos insights.
Hoje o projeto somente está constrituido em coletagem de dados.

# Obs :

  * Os scripts devem ser executados uma vez ao dia para o registro diário de informações.
  * Unir os csv e gerar uma base de dados histórica para a construção das analises em proximos passos
  
# Proximos passos  
  
  * Gerar plotagens com base na necessidade do negócio.
  * Encontrar os motivos se possíveis variações entre os dias
  * Comparar insights entre os locais/datas/variações
  * Implantar algoritimos de machine learning, caso for necessário

# Imagens

[Boi_Gordo](https://github.com/eotorres/Agro_arrobaboi/blob/boi_gordo/Capturar.JPG)
[CEPEA](https://github.com/eotorres/Agro_arrobaboi/blob/boi_gordo/Capturar1.JPG)
