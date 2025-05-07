# Projects for Applied Machine Learning:

## Project 3: White Wine Quality Prediction  

  ### Description:  
  This project uses ML models from built from scratch in PyTorch to predict the quality of white wine based on its chemical attributes. It includes
  data visualization, model training using gradient descent, and evaluation by cross-validation.

  ### Features:  
  - Data visualization using pandas, matplotlib, and seaborn for summaries and visualizations including heatmaps, histograms, violin plots, and joint plots to explore feature correlations
  - Gradient descent from scratch to train linear, multi-linear, and non-linear models with epoch training
  - 5 fold cross-validation to assess model generalization
  - 3 models implemented with gradient descent:  
    1. **Linear Regression** – using only alcohol as input  
    2. **Multi-linear Regression** – using multiple normalized features  
    3. **Non-linear Regression** – includes feature interactions
    
  
  ### Run and Compile:
  1. Type in command "pip install notebook"
  2. Type in command "jupyter notebook"
  3. Once web browser is open, navigate to HW3-4980.ipynb and open it
  4. Shift + Enter to run by cell or "Restart & Run All" to execute

  
  ### My Contributions: 
  - HW3-4980.ipynb


## Project 4: MNIST Digit Classification

  ### Description:
 This project uses the MNIST dataset from OpenML, consisting for 70,000 grayscale images of handwritten digits (0 through 9).
 The models are trained to perform:
 - Binary Classification (detecting whether a digit is one of 3, 7, or 8)
 - Digit Classification (ex. 3 vs. not-3)
 - Multi-digit classification (distinguishing between all 10 digits)


  ### Features:
  - Automatic MNIST dataset download and separation between testing and training datasets
  - Linear model uses sigmoid activation to determine whether it is 3, 7, or 8
  - Three-layer neural network with ReLu activations trained using CrossEntropy loss
  - Functions for training, testing, logging, and visualizing performance
  
  
  ### Run and Compile:
  1. Type in command "pip install notebook"
  2. Type in command "jupyter notebook"
  3. Once web browser is open, navigate to HW4-4980.ipynb and open it
  4. Shift + Enter to run by cell or "Restart & Run All" to execute
  
  ### My Contributions:
  - HW4-4980.ipynb
  

## Project 5: CIFAR-10 Convolutional Neural Network Classifier

  ### Description:
  Implements and compares several convolutional neural networks using PyTorch to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset contains60,000 32x32 color images
  accross 10 object categories, used for benchmarking computer cision models. 
  

 ### Features: 
 - Multiple CNNN structures:
   1. CNN: two layer-CNN with batch normalizations
   2. CNNold: a simpler variant with no normalization
   3. CNNnew: a deeper model that has Gaussian noise, dropout, and batch normalization
  - training and test loss tracking
  - accuracy reporting
  - CIFAR-10 prediction vizualization
 
  
  ### Run and Compile:
  1. Type in command "pip install notebook"
  2. Type in command "jupyter notebook"
  3. Once web browser is open, navigate to HW5-4980.ipynb and open it
  4. Shift + Enter to run by cell or "Restart & Run All" to execute
  
  
  ### My Contributions:
  - 4980-HW5.ipynb

  
