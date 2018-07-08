# Movie-Recommendations-using-Collaborative-Filtering

## Embedding matrix size 30
![curve1](embedding30.png) 
## Embedding matrix size 50
![curve2](embedding50.png) 
## Embedding matrix size 64
![curve3](embedding64.png)

**My work includes movie recommendations using collaborative filtering which is the most accurate way to recommend things. I have experimented with the size of embedding layer , batch_size and learning rate much and came to the final conclusion that particularly for this dataset the embedding layer of 30 was best in the sizes of 30,50 and 64 . Also the mean square error was better when kept layer size small. This might be due to the fact that the data might not be that complex to have feature extraction of upto 50 or 64. Extracting features upto this limit might have led the model to memorize and thus overfitting the data. The best mean square error achieves was of 0.8254.**


# Music/Songs Recommendation System
Task is to design a personalized recommendation system for music. Depending on experience level of the students, they can choose it to be content based or popularity based model. Content based model will require processing music features and recommending similar music. Extra points will be awarded if students can deploy the recommendation system through a web application or mobile application. 

**Skills Required:** Python, Object-Oriented Programming, Knowledge of Recommendation Systems, Matrix Factorization, Collaborative Filtering. Famous DL Libraries like Tensorflow or Keras. Optional Skills include Full stack web app, Android/iOS App Development.

## Resources to get started

1. [Understanding basics of Recommendation Engines](https://www.analyticsvidhya.com/blog/2015/10/recommendation-engines/)
2. [Overview video by Siraj Raval](https://www.youtube.com/watch?v=18adykNGhHU)
3. [Python Implementation of Popularity Based & CF Method](https://github.com/llSourcell/recommender_live)
4. [Hulu Blog Post on Applying Deep Learning to Collaborative Filtering](https://medium.com/hulu-tech-blog/applying-deep-learning-to-collaborative-filtering-how-hulu-builds-its-industry-leading-3b10a4ed7470)
5. [Quora Answer on Spotify Methods of Recommendation System](http://qr.ae/TUpVWo)
6. [Collaborative Filtering in Spotify](https://www.slideshare.net/erikbern/collaborative-filtering-at-spotify-16182818) - Requires Mathematics Understanding.
7. [Another Python Implementation](https://cse.iitk.ac.in/users/cs365/2014/_submissions/shefalig/project/)
8. [Thesis of Project on Music Recommender](https://www.politesi.polimi.it/bitstream/10589/6063/3/thesis-mrs-carlos-alvarez.pdf)
9. [Research Paper on Future Perspectives](http://webprojects.eecs.qmul.ac.uk/marcusp/papers/SongDixonPearce-CMMR2012.pdf)

### Senior Mentors for this Project

* [Nikhil Pandey](https://github.com/menikhilpandey)
* [Ronak Sakhuja](https://github.com/ronaksakhuja)
* [Rajat](https://github.com/rajat2712)
