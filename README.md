# Collection of Machine Learning Projects

These projects take inspiration from, "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" by Aurelien Geron. 

- Visit [Deepnote](<https://www.deepnote.com/>) for an online IDE, or setup your own Jupyter server.


### Installation



### Artificial Neural Networks using Keras

- [Notebook](10_intro_to_ML_with_Keras.ipynb)
    - Applications of Keras' [Sequential API] and [Functional API] to build both Regression and Classification models.
    - Use the Sub-classing API to Build Dynamic Models
    - Using Tensorflow's [Save and Serialize] tools
    - Implemented Checkout and Early Stopping [Callbacks]
    
[Sequential API]: https://keras.io/models/sequential
[Functional API]: https://keras.io/models/model
[Save and Serialize]: https://www.tensorflow.org/guide/keras/save_and_serialize
[Callbacks]: https://keras.io/callbacks

### Analysis using Skikit-Learn

- [Notebook](02_end_to_end_with_SKLearn.ipynb)
    - Explore data with descriptive statistics and visualisations
    - Clean and filter data using imputation strategies
    - Compares various models (Linear Regression, Random Forests & Support Vector Machines)
    - Leverage Skikit's [Pipeline API] and fine tuned models using [Grid Search] and [Randomized Search]
    
[Pipeline API]: https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html
[Grid Search]: https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
[Randomized Search]: https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html

### Training Deep Neural Networks

- [Notebook](11_training_deep_NN.ipynb)
    - Solving problems associated with training large neural network
    - Transfer and unsupervised pre-training
    - Optimisations that speed up training time
    - Regularisation techniques
