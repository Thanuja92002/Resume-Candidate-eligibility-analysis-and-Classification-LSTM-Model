# Resume-Candidate-eligibility-analysis-and-Classification-LSTM-Model
# Project Workflow

# 1. Data Collection
Collected labeled resume datasets splitted into test.csv and train .csv.

Each sample includes resume text and a corresponding eligibility label (e.g., suitable or not suitable).

# 2. Data Preprocessing
Text Cleaning: Removed stopwords, special characters, and performed lowercasing.

Tokenization: Split resumes into sequences of words or tokens.

Padding & Sequencing: Converted tokens into numerical sequences and padded them to uniform length.

Label Encoding: Transformed target labels into numerical format for training.

# 3. Feature Engineering
Extracted key NLP features (e.g., skills, degrees, experience keywords) using:

Named Entity Recognition (NER)

POS tagging

TF-IDF / word embeddings (optional for LSTM)

# 4. Model Building
Designed an LSTM-based neural network using Keras or PyTorch:

Embedding Layer

LSTM Layer(s)

Dense Layers with Dropout

Sigmoid/Softmax Output (depending on binary or multi-class classification)

# 5. Model Training
Split data into training and validation sets.

Trained model on processed data with appropriate loss function (e.g., binary cross-entropy) and optimizer (Adam).

Monitored performance using accuracy and validation loss.

# 6. Evaluation
Evaluated model on test data using:

Accuracy, Precision, Recall, F1-score

Confusion Matrix

Analyzed misclassifications to improve model/generalization.

# 7. Visualization
Plotted:

Training/validation loss and accuracy over epochs.

Confusion matrix.

ROC curve (if applicable).


