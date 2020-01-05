# related_faces
Use of Autoencoder for facial feature extraction then a small model on top to determine if faces are related

### Model
My idea is to use an autoencoder with 5x5 size in the hope of capturing more facial features that are more distinct. After that the encoder output is used for prediction. I simply concat the output of the encoder on two seperate images and put a small conv network on top.
