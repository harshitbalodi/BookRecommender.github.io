**BookRecommender.github.io**


[Click here for the demo](https://harshitbalodi.github.io/BookRecommender.github.io/)

In this application.I have created Popularity Based Recommender system and Collaborative Recommender System using a kaggle Bookdata set of 242135 books.

**Popularity Based Recommender system**

 Popularity Based Recommender system shows most popular 50 books from the dataset of 242135 books and only those book will be considered for Top Books which has highest average rating and atleasted rated by more than 250 users.

**Collaborative Filtering Based Recommender System**

Collaborative Filtering Based Recommender System shows 4 books and the conditions for recommended book is only those books which are rated atleast by more than 50 readers and only such readers rating will be count who has rated more than 200 books.Which means we are considering the readers who read a lot of books for these recommendations.These recommendations are acheived by creating a matrix of users and books and each book will behave like a vector and Euclidean distance
 between these vectors will come through cosine similarity function. A function Recommend will return 4 books which has the nearest cosine similarly from a book title which is passed as argument.
 
**Landing Page**

landing page also shows the Top 50 books using the Popularity based recommendation System

![Screenshot (437)](https://user-images.githubusercontent.com/96423397/173177393-ffbfb060-118e-4c4c-9c6c-34f6bc763ae0.png)

**Recommendation page **

Recommendation page default show a form to fill the book related to which you want recommendation.

![Screenshot (438)](https://user-images.githubusercontent.com/96423397/173178925-239830fa-fe92-4151-b4d4-c32f97c21c68.png)

fill a book and click at submit.
![Screenshot (439)](https://user-images.githubusercontent.com/96423397/173178914-9636d9d7-3e03-4074-b741-1edbc4f9a1a0.png)

shows 4 books similar to the filled book which may the user will like.
![Screenshot (440)](https://user-images.githubusercontent.com/96423397/173178993-9a4eac6c-1ea5-4354-9294-4ebe9fc8ebdb.png)

**Technologies used** HTML,CSS,JAVASCRIPT,PYTHON,FLASK,JUPYTER NOTEBOOK, BOOTSTRAP 

**Resources/References**

[video on BOOK RECOMMENDER SYSTEM](https://www.youtube.com/watch?v=1YoD0fg3_EM)

[Book recommendation Dataset](url)


