# Mask Detection trained model 

This model detects whether a user is wearing a surgical mask. <br>
Built with OpenCV, TensorFlow Keras API & vgg16 pretrained model. <br>

## Predict a Data Set :
**_TestMyModel.ipynb_** -> used to test your own data set<br>
You can test your own images by inserting them to the 'TestYourOwnImages' directory <br>
as of the following structure:

<pre>
└─TestYourOwnData
  └─masked
     │  masked001.jpg
     │  masked002.jpg
     └─  ...        
  └─unmasked
     │  unmasked001.jpg
     │  unmasked002.jpg
     └─  ...        
</pre>


## Real-time video : 
**_Real-Time-Stream.ipynb_** -> used to test a real time stream <br>
The application is still under development but it can work just fine when: 
* the camera scans only the face 
* used within proper brightness 

### Note :
* press 'ESC' button to exit 
* a sample video is attached. 

### Author
[Ahmad Aladdin](https://github.com/AladdinT) <br>
E-mail: tuhami.10.8@gmail.com

