# PROJETO_BRASILEIRAO_2023
Realizei um projeto utilizando Python + SQL + POWER BI para analisar uma base de dados do Campeonato Brasileiro de Futebol 2023

Recentemente realizei um projeto com uma base de dados do Campeonato Brasileiro de Futebol 2023. Esta base tinha apenas algumas informações sobre as 380 partidas realizadas durante o torneio, ou seja, era uma base bem simples e com poucas informações relevantes para o estudo (conforme o print do CSV). Porém, com o trabalho que realizei de ETL (extração, transformação e carregamento) acredito ter conseguido chegar em um resultado satisfatório.

Minhas Ações:
•	Exploração Inicial com SQL e Python: Iniciei meu estudo utilizando o SQL. Como utilizo o SQLite3, tiver que utilizar um pouco dos meus conhecimentos em Python para carregar o CSV, ajustar as colunas da base de dados e descobri como gerar um banco de dados SQLite3.
•	Transformação de Dados Cruciais: No SQLite3, criei “Views” importantes para gerar as “Tables” determinantes para uma análise mais aprofundada, como a pontuação de todos os times (calculando vitórias, empates e derrotas), estatísticas de gols (a favor e contra) e número de vitórias.
•	Integração com Power BI: Para uma análise mais detalhada, migrei para o Power BI. Encontrei um obstáculo ao descobrir que o Power BI não se conecta diretamente ao SQLite3, mas, com determinação, encontrei uma solução instalando um driver ODBC.
•	Criação de Dashboards Perspicazes: Utilizei o Power BI para criar dashboards informativos, relembrando funções e técnicas em DAX para realizar uma análise consistente dos dados.

Principais Insights:

•	Importância do Desempenho como Visitante: Descobri que o desempenho como visitante é crucial para uma boa colocação final no campeonato. Equipes que pontuaram consistentemente fora de casa tiveram melhor desempenho geral.
•	Padrões de Desempenho em Casa e Fora: As equipes de destaque alcançaram aproximadamente 60% de seus pontos em casa e 40% fora, reforçando a importância do desempenho como visitante.
•	Correlações com o Rebaixamento: Identifiquei que dos últimos 6 times com pior desempenho em casa, 4 foram rebaixados para a Série B, destacando a relevância do desempenho em casa para evitar o rebaixamento.
Obviamente que existem muitas outras possibilidades, poderia ter feito tudo diretamente em Python ou Power Bi, mas optei por utilizar diferentes ferramentas para aprimorar meus estudos e treinamento! Este foi um projeto rápido, mas muito interessante para mim do ponto de vista em utilizar várias ferramentas de trabalho, procurar soluções para dificuldades e conseguir extrair vasta possibilidade de análise dos dados!
Os arquivos estão disponíveis no meu GitHub, caso tenha interesse em visualizar a fundo o trabalho que desenvolvi!

#SQL #Python #Analisededados #PowerBI #DataAnalysis #FootballAnalytics #DataInsights #SportsAnalytics
