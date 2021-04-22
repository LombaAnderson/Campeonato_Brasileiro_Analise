# Campeonato_Brasileiro_Analise

Nesse dois conjuntos de dados carreguei somente a biblioteca Pandas do Python para fazer breve visualização de alguns dados do campeonato brasileiro de 2000 e 2021 retirados
do Kaggle. (https://www.kaggle.com/adaoduque/campeonato-brasileiro-de-futebol)

 
Os dados do banco de dados principal contêm 8319 linhas e 14 colunas sendo as colunas : ID, Rodada, Data,Horário, Dia, Mandante, Visitante,Vencedor,Arena, Mandante Placar, 	
Visitante Placar,Estado Mandante,Estado Visitante e Estado Vencedor

O outro conjunto de  dados intitulado dados_estatisticos possui 4570 linhas e 12 colunas sendo as colunas:
ID ,	Mandante, 	Chutes ,	Chutes a gol ,	Posse de bola 	,Passes ,	Precisão de passe ,	Faltas ,	Cartões amarelos ,	Cartões vermelhos ,	Impedimentos e 	Escanteios.

 Quantidade de dados que faltam em cada coluna do Data Frame 'dados'

dados.isnull().sum()

ID                    0
Rodada                0
Data                  0
Horário             357
Dia                   0
Mandante              0
Visitante             0
Vencedor              0
Arena                 0
Mandante Placar       0
Visitante Placar      0
Estado Mandante       0
Estado Visitante      0
Estado Vencedor       0
dtype: int64

Quantidade de dados que faltam nas colunas do Data Frame 'dados estatisticos'

dados_estatisticos.isnull().sum()

ID                      0
Mandante                0
Chutes                 50
Chutes a gol           50
Posse de bola          50
Passes                 50
Precisão de passe    2326
Faltas                 50
Cartões amarelos       50
Cartões vermelhos      50
Impedimentos           50
Escanteios             50
dtype: int64



