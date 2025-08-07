# Abstract of Project
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
dataset and on live experiments.

# Class Presentaion
Slide 22:
<img width="1280" height="720" alt="Slide22" src="https://github.com/user-attachments/assets/d29b49f0-0536-4987-8de0-eeffc34c1e9b" />

Slide 23:
<img width="1280" height="720" alt="Slide23" src="https://github.com/user-attachments/assets/9dbf46ea-c75d-40e1-8a35-331ff4f798da" />

Slide 27:
<img width="1280" height="720" alt="Slide27" src="https://github.com/user-attachments/assets/84dbce75-ea1e-40aa-9869-cb299b61eba5" />

Slide 28:
<img width="1280" height="720" alt="Slide28" src="https://github.com/user-attachments/assets/efe12d9f-11c0-4921-8238-bf546834025f" />

Slide 37:
<img width="1280" height="720" alt="Slide37" src="https://github.com/user-attachments/assets/5acb486d-a485-4d0a-a3c3-a22150e31654" />

Slide 41:
<img width="1280" height="720" alt="Slide41" src="https://github.com/user-attachments/assets/74456b21-3047-4f45-b4dc-70da9fb46d15" />

Slide 51:
<img width="1280" height="720" alt="Slide51" src="https://github.com/user-attachments/assets/f55f4231-aeb1-4f4c-acd4-62ba5040cb99" />
