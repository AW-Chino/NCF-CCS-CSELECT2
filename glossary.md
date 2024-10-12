# Machine Learning Glossary

## Dimensionality
**Meaning:** The number of features or attributes in a dataset.

**Description:** In simple terms, it's how many "columns" of information you have for each data point. High dimensionality can make analysis more complex and computationally expensive.

**Synonyms:** Feature space, attribute space

## Feature
**Meaning:** An individual measurable property or characteristic of a phenomenon being observed.

**Description:** Think of it as a column in your dataset. For example, if predicting house prices, features might include square footage, number of bedrooms, and location.

**Synonyms:** Attribute, variable, predictor

## Hyperparameter
**Meaning:** A parameter whose value is set before the learning process begins.

**Description:** These are the "knobs" you can adjust when setting up your model. For example, the number of trees in a Random Forest or the learning rate in gradient descent.

**Synonyms:** Model parameter

## Overfitting
**Meaning:** When a model learns the training data too well, including noise and fluctuations that don't represent the underlying pattern.

**Description:** It's like memorizing the textbook instead of understanding the concepts. The model performs well on training data but poorly on new, unseen data.

**Synonyms:** High variance

## Underfitting
**Meaning:** When a model is too simple to capture the underlying pattern in the data.

**Description:** It's like not studying enough for an exam. The model performs poorly on both training and new data because it hasn't captured the essential relationships.

**Synonyms:** High bias

## Regularization
**Meaning:** A technique used to prevent overfitting by adding a penalty term to the loss function.

**Description:** It's like adding a "complexity tax" to your model. This encourages the model to be simpler, which often leads to better generalization.

**Synonyms:** Weight decay, shrinkage

## Epoch
**Meaning:** One complete pass through the entire training dataset.

**Description:** Think of it as one full round of studying all your flashcards. Models often train for multiple epochs to improve their performance.

**Synonyms:** Iteration (in some contexts)

## Batch
**Meaning:** A subset of the training data used in one iteration of model training.

**Description:** Instead of looking at all data at once, the model looks at small "batches" at a time. This can make training more manageable and sometimes more effective.

**Synonyms:** Mini-batch

## Gradient Descent
**Meaning:** An optimization algorithm used to minimize the loss function by iteratively moving in the direction of steepest descent.

**Description:** Imagine rolling a ball down a hill and it naturally finds the lowest point. Gradient descent does this mathematically to find the best model parameters.

**Synonyms:** Method of steepest descent

## Cross-validation
**Meaning:** A resampling procedure used to evaluate machine learning models on a limited data sample.

**Description:** It's like taking multiple smaller quizzes instead of one big exam. This gives a more robust estimate of how well your model will perform on new data.

**Synonyms:** Rotation estimation, out-of-sample testing

## Ensemble
**Meaning:** A machine learning technique that combines several base models to produce one optimal predictive model.

**Description:** It's like asking for opinions from a group of experts instead of just one. This often leads to better and more robust predictions.

**Synonyms:** Ensemble method, multi-model technique

## Bias (statistical)
**Meaning:** The difference between the model's expected predictions and the true values.

**Description:** It's a measure of how far off, on average, your model's predictions are from the truth. High bias can lead to underfitting.

**Synonyms:** Systematic error

## Variance (statistical)
**Meaning:** The variability of model prediction for a given data point.

**Description:** It's a measure of how much your model's predictions would change if you trained it on different data. High variance can lead to overfitting.

**Synonyms:** Model sensitivity

## Feature Engineering
**Meaning:** The process of using domain knowledge to extract features from raw data.

**Description:** It's like creating new, more informative variables from your existing data. Good feature engineering can significantly improve model performance.

**Synonyms:** Feature extraction, attribute engineering

## One-Hot Encoding
**Meaning:** A process by which categorical variables are converted into a form that could be provided to ML algorithms to do a better job in prediction.

**Description:** It's like creating separate yes/no columns for each category. For example, "color" might become "is_red", "is_blue", "is_green", etc.

**Synonyms:** One-of-K encoding, dummy variable encoding

## Supervised Learning
**Meaning:** A type of machine learning where the model is trained on labeled data.

**Description:** It's like learning with a teacher. The model is given the correct answers (labels) during training and learns to predict these labels for new, unseen data.

**Synonyms:** Supervised machine learning

## Unsupervised Learning
**Meaning:** A type of machine learning where the model is trained on unlabeled data.

**Description:** It's like learning without a teacher. The model tries to find patterns or structure in the data without being told what to look for.

**Synonyms:** Unsupervised machine learning

## Reinforcement Learning
**Meaning:** A type of machine learning where an agent learns to make decisions by interacting with an environment.

**Description:** It's like learning through trial and error. The agent receives rewards or penalties for its actions and learns to maximize its total reward.

**Synonyms:** RL

## Classification
**Meaning:** A type of supervised learning task where the goal is to predict a discrete class label.

**Description:** It's like sorting items into predefined categories. For example, classifying emails as spam or not spam.

**Synonyms:** Categorization

## Regression
**Meaning:** A type of supervised learning task where the goal is to predict a continuous value.

**Description:** It's like predicting a number on a continuous scale. For example, predicting house prices or temperature.

**Synonyms:** Continuous prediction

## Clustering
**Meaning:** A type of unsupervised learning task where the goal is to group similar data points together.

**Description:** It's like organizing items into groups based on their similarities, without predefined categories.

**Synonyms:** Cluster analysis

## Neural Network
**Meaning:** A machine learning model inspired by the structure and function of biological neural networks.

**Description:** It's a series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates.

**Synonyms:** Artificial neural network (ANN), Neural net

## Deep Learning
**Meaning:** A subset of machine learning based on artificial neural networks with multiple layers.

**Description:** It's like having a very complex neural network that can automatically learn hierarchical features from data.

**Synonyms:** Deep neural learning, Deep neural network

## Confusion Matrix
**Meaning:** A table used to describe the performance of a classification model.

**Description:** It's like a report card showing how often the model correctly and incorrectly predicts each class.

**Synonyms:** Error matrix

## ROC Curve
**Meaning:** A graphical plot that illustrates the diagnostic ability of a binary classifier system as its discrimination threshold is varied.

**Description:** It's like a visual representation of the trade-off between the true positive rate and false positive rate at various classification thresholds.

**Synonyms:** Receiver Operating Characteristic curve