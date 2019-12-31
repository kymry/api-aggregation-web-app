# Nasa-ML-API

A work in progress. Check back soon!

A web app that aggregates astronomical data from the NASA api, feeds the data to ML models and allows the user to explore predictions. E.g. a user can enter a future data and the predicted weather on Mars on that date will be returned. 

- Built in Python using Flask and Bootstrap
- MongoDB used to store raw JSON from NASA apis
- SQLite used to store processed data in a relational manner that allows it to be consumed by ML models
- Scikit learn used for model creation and training (e.g SVM for Mars weather data)
- Python's Pickle used to serialize and store the learned models
- A custom built (granted simple) deep neural network built in Python that allows planet image classification (from our solar system) 
