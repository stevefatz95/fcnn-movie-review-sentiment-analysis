# Predicting Movie Review Sentiment Using Deep Learning  

This project explores the application of deep learning for sentiment analysis, specifically predicting the number of positive and negative movie reviews. Sentiment analysis is an essential tool for understanding customer opinions, which helps businesses make informed decisions, such as addressing negative feedback.  

To achieve this, the study employs **Fully Connected Networks (FCNs)**, a fundamental deep learning model, implemented using **TensorFlow**. The model is trained on the **IMDB dataset**, a widely used dataset containing labeled movie reviews for binary classification into positive and negative sentiments. The study follows the universal workflow outlined by François Chollet in *Deep Learning with Python*, ensuring a structured approach to model development and evaluation.  

## Important Note  

The provided file is an **HTML version** of the analysis and cannot be executed directly. It serves as a static report showcasing the methodology, results, and insights derived from the deep learning model.  

## Files Included  

- **`movie_review_sentiment_analysis.html`** – The report containing the analysis, methodology and results.  
- **`README.md`** – This file with project details and instructions.  
- **`LICENSE.md`** – Licensing information for the project.  

## Libraries and Tools Used  

- **TensorFlow** – Deep learning framework for building and training neural networks (including Keras as its high-level API).  
- **Scikit-learn (`sklearn`)** – Used for **k-fold cross-validation** to evaluate model performance.  
- **Pandas, NumPy** – Data manipulation and preprocessing.  
- **Matplotlib** – Data visualization.  

## Methodology  

1. **Data Loading & Preprocessing**: The IMDB dataset is loaded, tokenized, and vectorized to prepare it for deep learning models.  
2. **Model Implementation**: A Fully Connected Neural Network is built and trained using TensorFlow.  
3. **Cross-Validation**: The model is evaluated using **k-fold cross-validation** to ensure robustness.  
4. **Evaluation**: The model’s performance is assessed using accuracy and loss metrics.  
5. **Results Interpretation**: Insights are drawn from the predictions, highlighting key findings.  

## System Requirements  

- The analysis was conducted on a **Mac M1** system, but the methodology applies broadly across different hardware configurations.  
- **Python 3.8+** is recommended for similar implementations.  

## How to View the Report  

Simply open `movie_review_sentiment_analysis.html` in a web browser to explore the analysis and findings.  
