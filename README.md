# Recommender Systems with SURPRISE

This project evaluates multiple collaborative filtering algorithms using the **SURPRISE** library on the **MovieLens 100K** dataset. The goal is to compare different recommendation approaches and identify the algorithm with the lowest prediction error using cross-validation.

## Dataset
- **MovieLens 100K**
- 100,000 ratings
- 1,000 users
- 1,700 movies
- Stable benchmark dataset widely used in recommender systems research

## Algorithms Evaluated
The following algorithms were implemented and compared:

- **KNNBasic** — RMSE: 0.9787  
- **SVD** — RMSE: 0.9360  
- **NMF** — RMSE: 0.9625  
- **SlopeOne** — RMSE: 0.9453  
- **CoClustering** — RMSE: 0.9686  

## Evaluation Methodology
- 5-fold cross-validation  
- Evaluation metric: **Root Mean Squared Error (RMSE)**

## Results
Among the evaluated models, **SVD achieved the lowest RMSE**, indicating superior performance in predicting user ratings. This suggests that matrix factorization techniques are more effective at capturing latent user–item interactions than neighborhood-based methods on this dataset.

## Tools and Technologies
- Python
- Google Colab
- scikit-surprise
- NumPy
- SciPy

## Notes
This project was developed as part of a hands-on exercise to explore recommendation system algorithms and compare their performance on a real-world dataset.

## Author
**Felipe E. Ulloa**  
Technology & Data Professional  
GitHub: https://github.com/Felipe-Ulloa-CA

## License
MIT License

