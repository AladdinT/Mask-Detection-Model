Mask Detection trained model 
By: Ahmad Aladdin Mokhtar Tuhami
E-mail: tuhami.10.8@gmail.com

Built with OpenCV, TensorFlow Keras API & vgg16 pretrained model
using a Convolutional neural network in order to detect face masks in static images. 
The model can be used in Real-time video streams but not ready for production consuming yet.
You can test your own data by inserting the testing images to the directory 'TestYourOwnImages'
in this structure:
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
The application is still under developing but it can work just fine when: 
- the camera scans only the face 
- 30:40cm range is the most accurate
- the camera is in the same level as your face
- under proper brightness 
- press 'ESC' button to exit 
a sample video is attached. 