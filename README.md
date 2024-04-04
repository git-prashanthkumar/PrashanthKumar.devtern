Data exploration
1.Loading the dataset: first step is to load the dataset which contains both fake and real news. in these case our dataset file-name is news.csv.
2.Data preprocessing: cleaning the dataset, remove the unnecessary columns and rows that are not useful for classification example: titles,date, subjects etc.
3.Handling missing values: check for any missing values in dataset and handle them, like dropping rows with missing value can be considered.

Model building
1.TF-IDF vectorization: converting textual data into numerical using technique like TF-IDF vectorization.
2.Split data: Spliting the dataset into traning_data and testing_data in our case it is 20% of test data and 80% of traning data but it may vary based on the size of the dataset.
3.Initialize model: create an instance of the PassiveAggressiveClassifier model.
4.Train model: fit the model on the training data using TF-IDF transformed features and corresponding labels (real or fake).
5.Evaluate model:Once the model is trained evaluate its performance using testing data. Calculate metrics such as accuracy, precision to identify how well model can differentiate between fake and real news


![Alt text](fakenewsoutput.png "Optional title")
