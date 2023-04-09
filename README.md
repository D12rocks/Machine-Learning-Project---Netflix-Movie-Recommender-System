# Machine-Learning-Project---Netflix-Movie-Recommender-System
The project is a Netflix movie recommendation system that suggests movies to users based on their input movie


The Netflix Movie Recommender System is an application that uses machine learning techniques to provide recommendations to users based on their movie preferences.

The system is built using Python programming language and utilizes the scikit-learn machine learning library.
The project begins with loading the Netflix dataset, which includes information about various movies and TV shows available on the platform. 
The dataset has 8808 rows and 11 columns. The next step involves preprocessing the data by removing null values and stop words from the dataset. 
The TF-IDF vectorization method is used to convert words into numerical form for easy interpretation by the machine learning model.

The K-nearest neighbors (KNN) algorithm is used in the project to find the k-nearest neighbors to a given movie in the dataset based on the cosine similarity between their descriptions. 
The algorithm returns a list of indices of the k-nearest neighbors and their corresponding distances from the input movie.

The project utilizes a Graphical User Interface (GUI) to provide a user-friendly interface for users to enter the name of a movie and receive recommendations based on their preferences. 
The GUI is built using the Tkinter library, which provides tools for creating graphical interfaces in Python.

The project also includes a recommendation function that takes input from the GUI and processes it using the KNN algorithm to provide recommendations to the user. 
The function returns a list of recommended movies based on the cosine similarity of their descriptions to the input movie.

The project uses precision and recall as the evaluation metrics to determine the accuracy of the recommendations. 
The project achieves a precision score of 0.3 and a recall score of 0.08.

Overall, the Netflix Movie Recommender System is a successful project that utilizes machine learning techniques and a graphical user interface to provide recommendations to users based on their movie preferences. 
The project can be further improved by utilizing more advanced machine learning algorithms and expanding the dataset to include more movies and TV shows.
