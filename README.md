# Determine-the-iris-plant's-class<br>

Selecting the best ML model to predict iris plant's class<br>
Steps involved:-<br>
  • Perform EDA and Explore the features.<br>

  • Experiment using two different ratios of training, validation and test data ie (60-20-20),(80-10-10).<br>
    o Implement KFold Cross Validation (for model selection)<br>
    o Implement Grid Search to find optimal hyperparameters for any 3 algorithms(out of LR, SVM, MLP, RF, Boosting)<br>
    o Analyze the results on Validation set and test set and mention which model performed the best and why?<br>
    o Compare the performance of models(using precision, recall, accuracy, latency).<br>

###  Conclusion 1<br>

Best Model (as per (60:20:20) split) - Random Forest Classifier <Br> Random Forest Classifier models average accuracy for validation and test dataset is better than SVC and Ridge regression<br>

###  Conclusion 2<br>

Best Model (as per (80:10:10) split) - SVC <br> SVC models average accuracy for validation and test dataset is better than RandomForestClassifier and Ridge regression. Using SVC model we can also avoid overfitting<br>

###  Conclusion 3<br>

Models trained on 80:10:10 split has better accuracy on test dataset than models trained on 60:20:20 split.<br>
