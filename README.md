# Self-Driving-Car
A End to End CNN Model which predicts the steering wheel angle based on the video/image

### Dataset:
Download Dataset by Sullychen https://drive.google.com/file/d/0B-KJCaaF7elleG1RbzVPZWV4Tlk/view

### How to use
Use python3 train.py to train the model
Use python3 run_dataset.py to run the model on the dataset

### Observation
1) Using Adam optimizer's learning rate as 1e^-3 not getting proper output. It changes to 1e^-4.
2) Other hyperparameters used are :
   - 70%-30% train-test split
   - droupout 0.5
   - and in a final layer linear activation function is used.
3) CNN learns meaningful features.
