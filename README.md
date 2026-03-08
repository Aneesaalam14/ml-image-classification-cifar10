# Image Classification using Machine Learning

## Results
**Best Model:** SVM with **57.6% accuracy**

### Model Comparison
| Model | Accuracy |
|-------|----------|
| SVM (RBF) | 57.60% |
| Logistic Regression | 49.55% |
| SVM (Linear) | 49.25% |
| KNN | 45.70% |
| Random Forest | 45.65% |
| Decision Tree | 25.65% |

## Files in this Repository
- `best_model.pkl` - Trained SVM model (57.6% accuracy)
- `scaler.pkl` - For normalizing image features
- `pca.pkl` - For reducing dimensions from 1860 to 100 features
- `results.csv` - Complete model comparison results

## Classes
The model classifies images into 10 categories:
- airplane, automobile, bird, cat, deer
- dog, frog, horse, ship, truck

## Author
Aneesa Alam
