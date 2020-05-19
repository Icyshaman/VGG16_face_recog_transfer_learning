# VGG16_face_recog_transfer_learning
> **Overview**:
* Face recognition model using vgg16 architecture and transfer learning.

* VGG16:-
  * Consist of 16 layers
  * Input image shape is (224, 224, 3)
  
* Transfer Learning:-
  * When we use pre trained model after freezing all of its layers, removing its output layer, adding fully connected layer and output layer of our choice in order to create a new model is termed as transfer learning.
  * By using transfer learning we can train our model even with less computational power.
  
> **Changes you need to do/ Changes you can make**:
  * You can modify function fully_connected_head.
  * num_classes variable must be assigned with appropriate value, i.e., no. of classes possible.
  * train_data_dir must be assigned with training dataset path
  * validation_data_dir must be assigned with validation dataset path
  * nb_train_samples must be assigned with the no. of training samples available.
  * nb_validation_samples must be assigned with the no. of validation samples available.
  * epochs can be modified.
  * human_face_dict and human_face_dict_n must be modified.
  
