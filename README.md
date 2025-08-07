# Abstract
Object matching of image pairs is a wide area of
research in the field of computer vision. In this paper we
present an integration of state-of-the-art models to
perform similar or identical object matching.
We insert a pair of images, of object and scene. Inside
the scene the same or similar object can appear with
different perspectives, pose, or lightning. The main
model used to match the image pair is LightGlue [1], a
state-of-the-art feature matching model. For increasing
performance it is integrated with YOLO, an object
detection model. The assembled model of LightGlue
and YOLO detects the objects and iterates over the
regions of interest in the scene. Then Lightglue is
applied and finds the number of matched features,
accordingly the matched object is determined.
Implementing this integration into one framework
achieves greater results than Lightglue alone, while
tested on a customized dataset based on COCO
dataset and on live experiments
