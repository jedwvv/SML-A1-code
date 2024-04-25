### Code Authors - Name (Student ID):
- Jedwin Villanueva (834671)
- Yung Lau (1336607)
- Changfa Fu (1250020)

The separate models on different domains are in their appropriately named subfolders. For example, `domain_classifier` contain models for classifying which domain a text is from, wheras `domain12_models` contain models trained to classify human/AI text on the combined dataset of domain 1 and 2.

Since we used Jupyter Notebooks, we tried to explain the code logic within the code cells themselves.

Some models contain code that implemented training, validating and a final re-fitting but for some of these models the training and validation were done in the background via remote means (HPC, MRC, Google Colab) and those parts are not included; only the code for the final fitting/training with the chosen hyper parameters is included.

The final approach of using the neural network is in its own subfolder named `final_model`. Its notebook contains the training, validating and final fitting/training on the whole dataset, as well as the code to generate predictions on the test set.