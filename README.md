# NLP Text Generation with RNN-LSTM
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org) 
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Objective
The objective of this project is to explore text generation techniques by training an RNN-LSTM model. By understanding the nuances of language patterns, the model aims to generate text that is coherent and contextually relevant.

## Implementation Steps
1. **Read Text**: The initial step involves reading and preprocessing the text data which will be used to train the model.
2. **Text Processing**: Detailed preprocessing is conducted to prepare the data. This includes splitting the text into a sequence of words and their corresponding next words to form predictors and labels.
3. **Load Embedding**:
   - **Load Pre-trained Embeddings**: Utilization of pre-trained word embeddings to leverage existing language models.
   - **Prepare the Embedding Matrix**: Preparation of the embedding matrix that will be used by the RNN-LSTM model.
4. **RNN-LSTM Model for Text Generation**: Design and implementation of the RNN-LSTM model tailored for text generation.
5. **Model Management**:
   - **Save Model**: Save the trained model for future use.
   - **Load Saved Model**: Loading the saved model to continue training or for text generation.
6. **Generate Response with Variation**: Techniques to generate text responses with variations, enhancing the creativity and versatility of the generated content.
