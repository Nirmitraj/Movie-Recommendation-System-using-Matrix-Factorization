# Movie-Recommendation-System-using-Matrix-Factorization
This project implements a movie recommendation system using Matrix Factorization with PyTorch. It leverages user-movie rating data from the MovieLens dataset to learn latent features for both users and movies via embedding layers. The system predicts user preferences by computing the dot product of user and movie embeddings, trained using Mean Squared Error loss and optimized with Adam.

After training, K-Means clustering is applied to the learned movie embeddings to group similar movies together based on user behavior. The resulting clusters reveal that movies with similar genres and themes tend to fall into the same group — all without using any explicit movie metadata.
