Title: Spam News Detection

Tools Used:
- NumPy, Pandas, sklearn machine learning library
- NLP (Natural Language Processing) model

Working Procedure
- **Importing essential libraries**: The project starts by importing the necessary libraries such as
pandas and numpy.
- **Importing Dataset**: The dataset used in this project has been obtained from Keggle dataset
library
- **Refining the dataset**: The dataset was refined by getting rid of unnecessary data and
labelling the true news as 1 and fake news as 0
- **NLP**: Using Natural Language Processing, the dataset was edited to make it easier for the
machine to understand. This was achieved by converting the text to lowercase, using
WordNetLemmatizer to get rid of common stop words and finally vectorizing it to convert it
into binary
- **Splitting the Dataset**: The dataset was then split into a training and a testing model with 20%
of the data bring used for testing
- **Training the Model**: Finally, Naïve Bayes algorithm was used to train the model to interpret
fake and real news. This was done by importing the MultinomialNB package from sklearn
library. The model was tested with the testing dataset and was found to yield an accuracy of
70%
- **Random data Testing**: Some random user input data was also used to test the trained
machine learning model.
