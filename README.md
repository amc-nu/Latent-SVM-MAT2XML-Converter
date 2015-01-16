# Latent-SVM-XML-Converter

Converts MAT model files created by LatentSVM Release 5 (DPM) to OpenCV XML model files.

just run:
```
mat2xml_release5('your_trained_mat_model.mat', 'opencv_compatible_model.xml');
```
it will output the XML compatible file with OpenCV's LatentSvmDetector. 

Based on original OpenCV converter for release 3.
