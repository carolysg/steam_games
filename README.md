# Projeto Análise de Jogos da Steam

## Autores
Carolina Y. S. Goshima (carolinagoshima@gmail.com)
Gabriel G. de Oliveira Mourão (gb.mourao@hotmail.com).

## Dataset
Link: https://www.kaggle.com/datasets/antonkozyriev/game-recommendations-on-steam?select=games.csv

Este projeto utilizou uma base de dados com informações sobre jogos da Steam, obtida no Kaggle. \
3 tabelas diferentes foram utilizadas: games, users e recommendations.

* Games: app_id, title, date_release, win, mac, linux, rating, positive_ratio, user_reviews, price_final
* Users: user_id, products, reviews
* Recommendations: app_id, date, is_recommended, hours, user_id, review_id

As 3 tabelas foram inicialmente criadas no PostgreSQL, mas todas as queries foram realizadas no notebook.