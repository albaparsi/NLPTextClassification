# NLPTextClassification
Sarcasm Detection with TensorFlow/Keras
This project focuses on detecting sarcasm in text using machine learning techniques with TensorFlow and Keras. Sarcasm detection is a challenging natural language processing (NLP) task that involves understanding the subtle nuances and context-dependent nature of sarcasm in textual data.

Overview
In this project, we employ a deep learning approach to classify text as sarcastic or non-sarcastic. The model architecture includes an embedding layer followed by a global average pooling layer and dense layers with appropriate activation functions. We use binary cross-entropy as the loss function and Adam optimizer for training.

Project Structure
The project includes the following files and directories:

NLPTextClassification.ipynb: Jupyter notebook containing the code for training and evaluating the sarcasm detection model.
sarcasm_Headlines_Dataset.json: Dataset file containing sarcastic and non-sarcastic headlines.
vecs.tsv: TSV file containing embeddings of words for visualization.
meta.tsv: TSV file containing metadata (words) for visualization.
