## Mobile Price Range Classifier
### Steps that I performed
- Study,collect and import the data.
- Perform EDA(exploratory data engineering) on it to get better visualization
  - get info about data using df.describe()
  - checking na values by inbuilt function and custom one.
  - Find correlation between features and output.
  - Visualize it using seaborn pairplot or scatter plot.
  - Visualzing some features separately.
- Performing Feature engineering.
  - dropping columns which has less correlation and has not anything to do with our label
  - creating derived features
  - performing train_test_split
- Feature scaling
  - standard scaling
  - min max scaling
 - using pipeline
- Selecting the models
    - knn classfier
    - decision tree classifier
    - random forest tree clasfier
- training and evaluating models score
- Performing cross_validation
  - using k-fold validation
    - used 10 samples
    - trained ,test this three classifiers
### Knn and random forest performs the best.
- saving the model
