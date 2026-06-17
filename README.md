Jupyter Notebook: 

Load the dataset.(pd.read_csv(....))
Select useful features (Labels: id, title…) 
Create a dataframe with all the selected features. (movies = movies[[‘id’,’title’,’genre’,’overview’]])
Merge two features and create a new dataframe. (‘tags’=‘overview’+’genre’)
Drop the merged features from the previously created dataframe. (movies.drop(columns=[’genre’,’overview’]))
Convert text into vectors. (NLP: Bag of words, TFIDF)
Import CountVectorizer from sklearn.feature_extraction.text and enter max features and stop words which in this case will be english.
Use ‘fit_transform()’ method to convert movie tags into numeric values.
Use cosine similarity to calculate the angle as it makes real meaning.
Import cosine_similarity from sklearn.metrics.pairwise
Convert the similarity into a list and enumerate the list for vector conversion and this becomes the distance.
Create a function for recommendation.
Create two pickle files namely movies_list and similarity.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

VSCode:

Install streamlit.
Import pickle file and load it.
Create the front-end.
Used API for the movie posters.
