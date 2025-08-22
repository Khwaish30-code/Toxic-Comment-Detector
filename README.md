# Toxic Comment Detector

This project is implemented using Python and Gradio. It classifies text comments into positive, negative, or neutral sentiments based on a pre-trained model.

## Project Workflow

1. **Data Collection & Cleaning**  
   - Collect textual comments and preprocess them (remove stopwords, punctuation, etc.).

2. **Model Loading**  
   - Load a pre-trained sentiment analysis model for inference.

3. **Interface Creation**  
   - Build a simple Gradio interface to input comments and get sentiment predictions.

4. **Prediction**  
   - Input a comment into the interface and receive sentiment scores/output.

## Requirements

- Gradio  
- Transformers (HuggingFace)  
- TensorFlow   
- Pandas, NumPy  
