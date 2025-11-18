This project builds a Movie Recommendation System using the Movie dataset.
We implement two approaches: Naive Collaborative Filtering and Neural Collaborative Filtering (NCF).
The system predicts how much a user will like a movie by learning from rating patterns.
We also add Differential Privacy (Gaussian noise + DP-SGD) to protect sensitive user data.
EDA is performed to understand rating distributions, genres, and temporal trends.
Naive CF uses similarity between users to estimate missing ratings.
NCF uses embeddings and neural networks to learn deeper user–item interactions.
Models are trained and evaluated using metrics like RMSE/MAE.
Privacy methods increase noise in training but still provide useful predictions.
The project concludes with results, comparisons, and ideas for future improvements.
