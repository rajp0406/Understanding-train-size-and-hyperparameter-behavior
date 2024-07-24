# Understanding-train-size-and-hyperparameter-behavior
Understanding how train size and hyperparameter behavior affects the model fit( overfitting or underfitting )- Kaggle Competetion dataset
This dataset was taken from Kaggle's playground season 4 episode 6: Classification with an academic success dataset. The goal of this competition is to predict academic risk of students in higher education. https://www.kaggle.com/competitions/playground-series-s4e6


My goal was to understand and try out new learnings and findings and share it with everyone. The learnings from this competetion was to use yellowbricks learningcurvedisplay and validationcurve display to see how different hyperparametes and training size would affect the train and test performance. We want to check for overfitting or underfitting. 


Currently for validation curve you can only see use 1 parameter to check the fit. But another approcah would be to find the ideal hyperparameter at each step. For. e.g. In the first once I found out the trade off for max_depths, I can use this max_depths value inorder to find trade off for learning_rate hyperparameter in the next step. 


The benefit of using this you have a visual idea of how hyperparameters are affecting the performance.

Now the learning curvedisplay can give you a visual idea of how train and test size affetc the performance.

