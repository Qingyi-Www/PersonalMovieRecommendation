# Personal Movie Recommendation

## Introduce:
It finds other users who are most similar to a given user by KNN algorithm based on the similarity between users, and recommends unrated movies to users based on the voting weights of these similar users 
Modify the input on this basis and generates Quantized Image and Color Bar of related posters.

## Document Test：
I randomly selected 3 users and found that the recommended movies were different and all generated color bars.
Process final result files: User2.ipynb, User5.ipynb, User8.ipynb

## Based on the algorithm:
Movie-Analysis by LJSthu (https://github.com/LJSthu/Movie-Analysis)
reference: movie-poster-color-bars by joshwcheung (https://github.com/joshwcheung/movie-poster-color-bars)

## Database use:
movie.csv: https://www.kaggle.com/datasets/neha1703/movie-genre-from-its-poster
test.csv: https://github.com/LJSthu/Movie-Analysis/blob/master/personal_recommender/train.csv
train.csv: https://github.com/LJSthu/Movie-Analysis/blob/master/personal_recommender/train.csv
Poster.csv: https://github.com/LJSthu/Movie-Analysis/blob/master/data/personal/movies.csv
