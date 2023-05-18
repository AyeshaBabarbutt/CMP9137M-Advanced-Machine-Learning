# CMP9137M-Advanced-Machine-Learning
**SuperMarioBros2-v0**
 A Python script that trains an agent to play the Super Mario Bros game using reinforcement learning.
 It uses the Gym and gym-super-mario-bros libraries to create and interact with the game environment. 
 The agent learns to play the game by using a Deep Q-Network (DQN) algorithm, which is implemented in the "Mario" class.
 The script includes various helper functions and classes for preprocessing the game state, defining the neural network
 architecture, and managing the agent's memory and training process. It also includes code for saving and loading the trained model. 
 To run this script, you need to have the required libraries installed and access to a GPU if you want to enable GPU acceleration. 
 You can run the script in a Python environment that has all the dependencies installed.
**Visual Question Answer**
Mount your Google Drive by executing drive.mount('/content/drive'). This allows you to access files and directories in your Google Drive.
Install the required libraries by running !pip install -U 'Pillow>=5.2.0' torch torchvision pillow einops. This will install the necessary packages for image processing, deep learning, and tensor operations.
Clone the necessary GitHub repositories by executing !git clone https://github.com/Cyanogenoid/pytorch-vqa.git and !git clone https://github.com/Cyanogenoid/pytorch-resnet.git. These repositories contain additional code and models required for the VQA task.
Download the pre-trained model by running !wget https://github.com/Cyanogenoid/pytorch-vqa/releases/download/v1.0/2017-08-04_00.55.19.pth. This model will be used for the VQA task.
Define the paths for your train and validation datasets by setting train_path and val_path variables.
Set the desired batch size, number of epochs, and learning rate by modifying the batch_size, num_epochs, and learning_rate variables.
Create a custom VQADataset class by defining the dataset's path, split (train, validation, test), and any required transformations. 
This class will handle loading and processing the images and questions.
Define the VQAModel class, which consists of a pre-trained ResNet-152 model for image feature extraction, a linear layer for feature 
projection, an LSTM layer for question processing, and a linear layer for answer generation.
Load the pre-trained weights and vocabulary for the VQAModel.
Implement any additional functionality or modifications to the code as needed.
