# Image Classification
Image Classification Android Application using TensorFlow Lite

Image Classification on Android using TF Lite
To use this app, you need to have a pre-trained image classification TF Lite model. This app can be used for any custom-trained model.

Steps:
1. It is assumed that you already have a TF Lite image classification model of yourself.

2. Clone the repository on your local machine.

3. Copy your .tflite model and its corresponding label.txt file inside Image Classification -on-Android-using-TF-Lite\app\src\main\assets folder.

4. Open the project in Android Studio and let the project build itself.

5. Open MainActivity.java file and edit Line 169 by replacing cartoon_model.tflite with the name of your TF Lite model. Also edit Line 231 by replacing cartoon_labels.txt with the name of your model's label file.

6. Build and run the app on your physical device or on emulator.
