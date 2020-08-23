# WildFireSmokeDetection 
Submission for hackathon conducted by AI For Mankind (https://aiformankind.org/). See details of hackathon at https://aiformankind.org/lets-stop-wildfires-hackathon-2.0/


Thanks to AIManKind for providing Quick Start Demo https://github.com/aiformankind/wildfire-smoke-detection-camera
and providning label Image Data Set.

### Saved Model
Submitted fined tune model is with EfficientDet-d3 using TensorFlow.

Data Set - 737 images. After augmenting (Horizontal Flip and added brightness form 0% to 23%). 

   Training Images : 1739
   Validation Images : 111


### Resources

WildFire Resources
- [FUEGO Wildfire Detection Slides by Kinshuk Govil](https://tinyurl.com/rbrn4oq)
- [Wildland Fire Assessment System] (https://journals.sagepub.com/doi/pdf/10.1155/2014/597368)
- [How Wildfire Works] (https://science.howstuffworks.com/nature/natural-disasters/wildfire.htm/printable)


Tensorflow Resources
- [Tensorflow Quickstart](https://www.tensorflow.org/tutorials/quickstart/beginner)
- [TF Objection Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)
- [Object detection inference] (https://github.com/tensorflow/models/blob/master/research/object_detection/colab_tutorials/inference_from_saved_model_tf2_colab.ipynb)
- 

Other Resources
- [Faster RCNN ResNnet](https://towardsdatascience.com/faster-r-cnn-object-detection-implemented-by-keras-for-custom-data-from-googles-open-images-125f62b9141a)
- [Train EfficientDet in TensorFlow](https://www.youtube.com/watch?v=yJg1FX2goCo)
- Data Augmentation using [roboflow](https://roboflow.com/)
- [Train object detection with Keras](https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/)
