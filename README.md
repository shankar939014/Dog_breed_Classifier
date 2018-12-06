# Dog_breed_Classifier
In this project, I have built a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

# Project Execution and Dependencies

 1) Clone the repository and navigate to the downloaded folder.
 
     ``` python
     git clone https://github.com/shankar939014/Dog_breed_Classifier.git
     
     ```
 
 2) If you have GPU, train the CNN network using the same else it is recommended to use Cloud service suchs as AWS, GCP. They are providing
     Virtual Machines with pre installed libraries and frameworks. I have taken aws p3.2x instance which is having pytorch 0.4 with cuda 9.
     
 3) Download [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip) and unzip it.
 
 4) Download [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) and unzip it.

 5) Open the jupyter notebook dog_app.ipynb
  
      ```
      jupyter notebook dog_app.ipynb
      
      ```
 6) In order to make use of pre trained model (VGG16) load the weights(model_transfer.pt) after initializing the model.
    
