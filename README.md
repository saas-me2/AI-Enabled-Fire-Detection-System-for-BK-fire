# AI-Enabled-Fire-Detection-System-for-BK-fire
An app integrated with a surveillance camera connected to fire suppression robots. This system allows localization of the fire with the help of an including an AI algorithm and extinguishes it locally in an early stage before it spreads

The proposed method is intended to be a replacement or supplement to conventional fire detection sensors without the need for installation of a huge infrastructure.

bIt involves building and training deep learning models using TensorFlow and Keras, using pre-trained models such as VGG16 to build a custom model for our classification task: fire, no-fire. The Dense, Flatten, and Dropout layers from Keras are used to build custom model architectures on top of the pre-trained models.

The project also uses various optimization algorithms (SGD, Adam, and RMSprop) and regularization techniques (l1, l2, and l1_l2) to train the models. The LearningRateScheduler, ModelCheckpoint, and TensorBoard callbacks from Keras are used to monitor and improve the training process.
