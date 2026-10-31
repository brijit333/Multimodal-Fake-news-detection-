# Multimodal Fake News Detection

A research prototype that analyses a post's headline and associated image
to classify it as likely fake or real.

## Technologies
- DistilBERT for text feature extraction
- ResNet50 for image feature extraction
- PyTorch for deep learning
- Multimodal fusion for classification
- Streamlit for the web interface

## Run locally

Install dependencies:

    pip install -r requirements.txt

Run the application:

    streamlit run app.py
    https://h5zyvbdqh8behbg7bhp36n.streamlit.app/
    https://www.kaggle.com/code/brijit321/fake-news-detection-project/edit

## Project structure

- app.py: Streamlit application
- fakenews_core.py: Feature extraction and model definitions
- models/: Trained model and configuration files
- outputs/: Evaluation results and visualisations

The model is a research prototype trained using the Fakeddit dataset.
Predictions should be treated as signals, not definitive fact-checks.
<img width="1667" height="832" alt="image" src="https://github.com/user-attachments/assets/41a07f1e-fc47-47d1-95d2-0e2a2c0a88e1" />
<img width="1808" height="840" alt="image" src="https://github.com/user-attachments/assets/5b8bdf07-f850-4856-814b-a342376d7bd9" />

