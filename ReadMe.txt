Mask Detection trained model 
By: Ahmad Aladdin Mokhtar Tohamy
E-mail: tuhami.10.8@gmail.com

Built with OpenCV, TensorFlow Keras API & vgg16 pretrained model
using a Convolutional Neural Network (CNN) in order to detect face masks in static images. 
The model can be used in Real-time video stream as well but not ready for production consuming yet.
You can test your own data by inserting the images to be tested to the directory 'TestYourOwnImages'
as of the following structure:
```
TestYourOwnData/
    masked/
        masked001.jpg
        masked002.jpg
        ...
            
    unmasked/
        unmasked001.jpg
        unmasked002.jpg
        ...
'''
Real-time video : 
The application is still under development but it can work just fine when: 
- the camera scans only the face 
- under proper brightness 
Note :
- press 'ESC' button to exit 
- a sample video is attached. 
