Code for generating triplets from a given dataset and training FaceNet on triplet loss to separate face embeddings.

# Versions
1) Python     - 3.8
2) Tensorflow - 2.5.0
3) Keras      - 2.4.3 

# Data Description
1) Georgia Tech Face Database - http://www.anefian.com/research/face_reco.htm

From all the images in the above dataset, cropped face images were extracted using the Multi-task Cascaded Convolutional Networks (MTCNN) package in Keras.  
'Sample Data' consists of the first ten generated triplets of the created dataset.
    
# Model
'triplet_generator.ipynb' was used to generate the triplets, the FaceNet model was trained on the triplet loss using the implementation available at the Keras website: https://keras.io/examples/vision/siamese_network/  
FaceNet weights can be obtained here: https://github.com/nyoki-mtl/keras-facenet
