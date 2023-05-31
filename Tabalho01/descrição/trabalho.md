# Trabalho prático de aprendizado de máquina 

* **Equipe:** Danilo Carneiro Teles (470444), Henricky de Lima Monteiro (475075)
-------------

## Problema:

Analisar quais eventos influênciam no resultado de uma partida rankeado do jogo League of Legends, jogo do estilo MOBA onde duas equipes de 5 campeões que se enfrentam em 3 rotas e um intermédio delas, chamada *jungle*, que tem por objetivo destruir torres para acessar a base e destruir o centro da mesma. Vamos dividir o problema em duas partes: Analisar as condições, dentro de partida, que influênciam na vitória de uma equipe; E se as condições fora de partida, como campeões selecionados (picks) e banimentos de campeões (bans), influênciam na vitória do time.

* **Database:** [League of Legends Ranked Games](https://www.kaggle.com/datasets/datasnaek/league-of-legends?select=games.csv) (51490, 61)

* **Tipo de problema:** Classificação (Aprendizagem supervisionada)
* **Features:** O dataset tem 61 features e delas vamos filtrar os eventos que mais influênciam na vitória de um time.
* **Output** Classificar o ganhador de uma partida divididos em duas condições, dentro e fora da partida, como quais os eventos dentro do jogo e relação dos campeões, picks e bans, que mais influênciam no resultado final da partida. 