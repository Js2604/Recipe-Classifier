# Recipe-Classifier
- Built a classifier using python, pandas, and Keras to classify recipes into cuisine categories (ex. Chinese) based on their ingredient lists
- General process:
  1. Compile a list of the 5000 most common ingredients that appear in recipes throughout the dataset.
  2. Using a substring comparison of the other ingredients against the list of most common ingredients, map these ingredients to the most similar matches found in the common list
  3. After cleaning and preprocessing these ingredient names, partition the data into training and testing sets.
  4. Train the model using Keras
  5. Evaluate results.
