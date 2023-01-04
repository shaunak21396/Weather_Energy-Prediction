# Weather_Energy-Prediction
Weather prediction using a Neural network trained on the data of weather records and solar energy generation

<h2>What I learned:</h2>

- <b>Application of the following Python libraries/packages:
  1. Numpy
  2. Matplotlib
  3. Pytorch
  4. Pandas
  5. Scikit-learn

- <b>Data preprocessing is vital. Data cleaning (removing outliers) followed by adding features and normalization prepare data for efficient machine learning.
- <b>Dataset needs to be split into Training and Validation subsets for learning and testing the model.
- <b>Plotting Loss vs epoch for illustrating the comparision between Training Error vs Validation Error.
- <b>How the choice of the basis functions determine the performance of a model. The First model (trained with SKlearn) performed poorer than the Second model (trained with Torch) from the accuracy point of view. In a sense, the basis functions in the First model are chosen by us. However, the basis functions in the Second model are learned by the model itself. Therefore, the Second model could learn the basis functions so as to map the data X to the space where model could make better classification. That's why we get better performance in the Second model.
