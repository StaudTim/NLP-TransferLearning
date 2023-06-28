# Transfer Learning - Fake News Detection
This is a demo for the course _Aktuelle Themen der KI_, Deggendorf Institute of technology for the topic: "Transfer Learning in NLP".

For this demo we are going to build a model for Fake News Detection using BERT (Bidirectional Encoder Representations from Transformers) as a starting point.

First, we look at the data set and prepare it so that our model can process it.
Then we take a closer look at BERT. In doing so, we consider the functions for which it was originally trained.
We then create a model based on BERT. After that, let's look at how layers of the model can be frozen so that their weights don't update during subsequent training.
Finally, the performance of the model is evaluated.

## Installation
Make sure to install Jupyter Notebook by running this command in your terminal:
```sh
$ pip install notebook
```

## Getting Started
### 1. Launch Jupyter Notebook
Open a terminal and navigate to the directory where your Jupyter Notebook file is located. 
Run the following command to start Jupyter Notebook:

```sh
$ jupyter notebook
```

This will launch the Jupyter Notebook server and open a web browser.

### 2. Access the Notebook
In your web browser, you should see the Jupyter Notebook interface. 
Navigate to the directory where your notebook file is located and click on its name to open it.

### 3. Run the Notebook
Once the notebook is opened, you'll see the notebook's cells, which can contain code or text. 
To run a specific cell, click on it and then press Shift + Enter or click the "Run" button in the toolbar. 
The code in the cell will be executed, and any output will be displayed below the cell.