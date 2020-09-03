# Human-Posture-Recognition

Human Posture detection actually tells us about the posture of the image by
checking the key-points of their body. With the help of the key points which
are retrieved from heat maps , we can join the key-points using Part Affinity
Fields(PAF) through which we can compare and tell the position in which you
are accordingly.
Using Tensor-Flow as backend and Keras framework this model(Open Pose)
has been developed which has 4 layers in it. Convolution is done in between
layers to obtain the key-points.
This helps us to know the posture of the person in the image by which we can
maintain our posture according to our convenience.
