# Name-Entity-Recognition-NLP
**Named Entity Recognition Using BI-LSTM**

This project uses BI-LSTM to perform Named Entity Recognition (NER) on text data. NER is a subtask of information extraction that seeks to locate and classify named entities in text into predefined categories, such as person names, organizations, locations, medical codes, etc.

The BI-LSTM model is a type of recurrent neural network (RNN) that is capable of capturing the context of each word in a sequence by processing the sequence in both forward and backward directions. The model architecture consists of an embedding layer that maps each word in the input sequence to a vector, a bidirectional LSTM layer that processes the sequence in both forward and backward directions, a time-distributed layer that applies a dense layer to each time step of the output sequence, and finally, a softmax activation layer that outputs the predicted entity class for each word in the input sequence.

**Dependencies**
This project requires the following Python libraries:

numpy
pandas
matplotlib
seaborn
scikit-learn
tensorflow

**Graphs And Overview**
![image](https://user-images.githubusercontent.com/67000746/234536090-781dd65c-d6ae-4892-a468-210663035dab.png)

![image](https://user-images.githubusercontent.com/67000746/234536181-7f559683-196d-4065-9759-a3fd77b651b0.png)

![image](https://user-images.githubusercontent.com/67000746/234536234-29f8f8ea-02aa-4737-9028-dcb96ecefb11.png)

**Accuracy**
![image](https://user-images.githubusercontent.com/67000746/234536339-e3cb3ce1-8b4f-42d8-aeb7-e14d28f29312.png)

**Train and loss Graph **
![image](https://user-images.githubusercontent.com/67000746/234536647-102f1ed1-e32f-4666-b7cb-a5d7fca947a4.png)


**Usage**
To use this project, follow these steps:

1) Clone the repository to your local machine.
2) Install the required dependencies by running pip install Dependencies in your terminal.
3) Open the NER_using_BI_LSTM.ipynb notebook in Jupyter Notebook or your preferred Python IDE.
4) Follow the steps in the notebook to train the model on your own data or to test the pre-trained model on sample data.
5)View the generated graphs using matplotlib and seaborn to visualize the results.

**Contributing**
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

**License**
This project is licensed under the MIT License.
