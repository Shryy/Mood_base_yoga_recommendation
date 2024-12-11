
# Mood-Based Yoga Recommendation System

## Problem Understanding
The system is designed to recommend personalized yoga routines based on the user's mood, which is detected through sentiment analysis of their input text. The goal is to enhance the yoga practitioner's experience by aligning the routine with their emotional state.

## Approach
- **Sentiment Analysis**: The user's mood is predicted from text input using a sentiment analysis model trained on a labeled dataset of emotional text.
- **Yoga Routine Recommendation**: Based on the predicted mood, a yoga routine is suggested that matches the user's emotional state.

## Data Preprocessing
- Data was sourced from a custom dataset containing emotional text paired with labels for various moods.
- Text data was preprocessed using standard NLP techniques like tokenization and vectorization.

## Model Architecture
- I used a **Logistic Regression** model for sentiment analysis.
- The model was trained on the processed data and evaluated based on accuracy and other performance metrics.

## Results
- The model achieved **[accuracy]** on the test dataset.
- Example mood predictions: "happy", "sad", "angry", etc.

## Next Steps
- Explore more complex models like **SVM** or **Deep Learning** for improved accuracy.
- Implement a user interface (e.g., HTML/Flask app) to interact with the model.
- Integrate yoga video links (e.g., YouTube) to provide complete session recommendations.
- Fine-tune the model using additional training data.

## How to Run the Code
1. Clone the repository: `git clone https://github.com/Shryy/Mood_base_yoga_recommendation.git`
3. Run the notebook or Python script in colab for sentiment analysis and yoga recommendation.
