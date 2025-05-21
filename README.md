This repository contains the following files, their relevance is indicated against their name:
1. two_body_dataset.csv : Contains 10,915 datapoints and is generated using the dance_of_planets_datagen.ipynb file. This serves as the final dataset for this project. This dataset contains 9 columns m1,m2 which are single valued then x1_0,x2_0,v1_0,v2_0 which are 2D vectors followed by a singled valued time t, and then predicitions genertaed using the numerical sovler which are 2d vectors.
2. fina_dop: An h5 file containing the final weights and biases for the final mode.
3. dance_of_planets_datagen.ipynb : Code to generate the dataset.
4. dance_of_planets_nn_final.ipynb: Code for the final model used to make the necessary predicitions. Further, contains the input cell reqiured by the task.
