This project implements a movie recommendation system using matrix factorization techniques optimized with various stochastic gradient descent (SGD) methods. The system predicts user ratings for unseen movies by learning latent features of both users and items from a sparse user-item ratings matrix.

Key features:

1. Matrix Factorization to capture user–movie interaction patterns.

2. Implementation of multiple SGD optimization techniques (vanilla SGD, mini-batch SGD, momentum-based SGD, etc.) for performance comparison.

3. Evaluation using metrics like RMSE and MAE.

4. Configurable parameters such as learning rate, regularization, and number of latent factors.

5. Trained on MovieLens dataset for realistic recommendation scenarios.

The project provides insights into how different SGD variants affect convergence speed, accuracy, and generalization in recommendation systems.
