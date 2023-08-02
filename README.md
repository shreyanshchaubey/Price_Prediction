How I Used MongoDB along with ML to predict Airbnb Rental Prices 

We're talking about:

MongoDB
Tensorflow
Spark
And more...
The code in this collection is like a foundation for my talks about Machine Learning. It demonstrates how you can combine MongoDB and Keras, which is part of Tensorflow.

Just like in my demonstration with MongoDB and R, I believe it's super important to use a database that's easy to work with. This is key for developer productivity.

Here's what the example shows:

How you can use the Aggregation Pipeline to get important information from different types of data.
Storing models in MongoDB.
Using the Aggregation Pipeline again to pick the best model from different training tries.
All this helps reduce the work on the computer when training models and lets you train and use models continuously. This is extra helpful when you're using methods that combine lots of models.

There's a Slide-Deck and a Demo to help you understand more.

The Demo is in the "Machine_Learning_With_MongoDB_And_Tensorflow_Keras_Public.py" file.

Getting Things Ready:

Create a free account at http://atlas.mongodb.com.

Make a Cluster (M0 is free).

Click on the three dots next to the connect button and choose to load sample data.

After the cluster is ready, adjust the connection-string to MongoDB Atlas and load the sample data.

client = MongoClient("MongoDB-Connection-String")
Add your IP address to the IP-Whitelist in the security section. This is important for connecting to the cluster.

Now you're ready to run the Demo.

You'll need some packages:

PyMongo: [https://api.mongodb.com/python/current/]
Tensorflow: [https://www.tensorflow.org/]
Scikit-Learn (SkLearn): [https://scikit-learn.org/stable/]
Matplotlib: [https://matplotlib.org/]
Pandas: [https://pandas.pydata.org/]
NumPy: [https://numpy.org/]
Seaborn: [https://seaborn.pydata.org/]
Pickle (You might need to change this): [https://docs.python.org/3/library/pickle.html]
This comment was manually created using Markdown at: https://dillinger.io/

Just like how I showed you how to do things on Airbnb, you can do similar things on other apps too. This example demonstrates how to efficiently use Machine Learning using Python, MongoDB, and Tensorflow (Keras).
