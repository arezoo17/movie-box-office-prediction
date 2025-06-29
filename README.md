# Movie Box Office Prediction 🎬📊

This project predicts the total box office revenue for movies using the Metacritic dataset and additional features derived from expert reviews, metadata, and engineered variables.

## 👥 Team

This project was developed as a group assignment by a team of four students as part of our academic coursework. Each team member contributed to different aspects such as data preprocessing, feature engineering, modeling, explainability, and documentation. Markdown comments in the notebooks are tagged with the contributor's name where applicable.

## 📁 Project Structure

- `Prediction_ML.ipynb`: Main notebook including data loading, merging, feature engineering, model training, and explainability (SHAP, Counterfactuals).
- `Transformer_1.ipynb`: Review embedding using transformer models (pre-release reviews only) with PCA applied.
- `expert_transformer_1.xlsx`: Processed PCA result of review embeddings, merged back into the main dataset.
- `ReadMe.pdf`: Detailed project breakdown and steps.

## 🔍 Main Steps

1. **Data Preparation**: Merged Metacritic and sales datasets, handled missing values using median and imputer comparison.
2. **Exploratory Analysis**: Visualized key relationships between variables and box office performance.
3. **Feature Engineering**:
   - Statistical filtering (ANOVA, Pearson correlation)
   - One-hot encoding and dimensionality reduction (SVD)
4. **Review Embedding**:
   - Extracted expert reviews dated before release
   - Embedded text using transformer, reduced with PCA
5. **Modeling**:
   - Trained Linear Regression, Random Forest, and ANN models
6. **Explainability**:
   - Applied SHAP for global and local importance
   - Used counterfactual explanations for interpretability

## 🧠 Key Techniques

- NLP with Transformers & PCA
- ANOVA, Pearson Correlation
- SHAP and Counterfactuals for Explainability
- Regression models (Linear, RF, ANN)

## 💾 Dataset

This project uses the Metacritic dataset and merged it with box office sales data. Due to licensing restrictions, raw datasets are not included in this repository.

