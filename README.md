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
<img width="1280" height="720" alt="Slide22" src="https://github.com/user-attachments/assets/12087d8e-fc2f-4a28-a8e6-c637d4025b74" />
<img width="1280" height="720" alt="Slide21" src="https://github.com/user-attachments/assets/3c298319-2811-43d2-9fec-6856942ef997" />
<img width="1280" height="720" alt="Slide20" src="https://github.com/user-attachments/assets/4114351e-a0d3-4ece-9e2b-d551fe8e6733" />
<img width="1280" height="720" alt="Slide19" src="https://github.com/user-attachments/assets/d91b705e-41ae-443e-b486-11641798b6f7" />
<img width="1280" height="720" alt="Slide18" src="https://github.com/user-attachments/assets/f215a1ce-e23c-4138-b0a6-aa2796d3d6c8" />
<img width="1280" height="720" alt="Slide17" src="https://github.com/user-attachments/assets/ebfd0985-3954-4936-acc7-09067add5047" />
<img width="1280" height="720" alt="Slide16" src="https://github.com/user-attachments/assets/69df7ed3-e367-452c-8e70-30ba27f558d7" />
<img width="1280" height="720" alt="Slide31" src="https://github.com/user-attachments/assets/a25a3d43-ad7a-4072-b2c3-517a85fec8b3" />
<img width="1280" height="720" alt="Slide30" src="https://github.com/user-attachments/assets/84509754-83db-4f45-a9ba-e36129763649" />
<img width="1280" height="720" alt="Slide29" src="https://github.com/user-attachments/assets/5352d6f7-4cdd-4e84-9d91-96875c022fa4" />
<img width="1280" height="720" alt="Slide28" src="https://github.com/user-attachments/assets/127b8121-9837-4ab1-bbb9-d90d4d8d3bda" />
<img width="1280" height="720" alt="Slide27" src="https://github.com/user-attachments/assets/e89ee967-6039-459d-913b-5641548ce513" />
<img width="1280" height="720" alt="Slide26" src="https://github.com/user-attachments/assets/4c58868a-2a14-4536-932e-d0c0a74ae3fe" />
<img width="1280" height="720" alt="Slide25" src="https://github.com/user-attachments/assets/278ae962-0e29-4b3b-9733-f458be611031" />
<img width="1280" height="720" alt="Slide24" src="https://github.com/user-attachments/assets/a4569bc5-57d8-404a-a983-288b826f820c" />
<img width="1280" height="720" alt="Slide23" src="https://github.com/user-attachments/assets/a9dd0782-aab7-4942-8fee-aa0e97ecbae0" />
<img width="1280" height="720" alt="Slide52" src="https://github.com/user-attachments/assets/7e278c8a-1e65-4276-bf9d-3d6684d7b777" />
<img width="1280" height="720" alt="Slide51" src="https://github.com/user-attachments/assets/9438676e-2e75-4ac9-a7df-9aeb0abfba4b" />
<img width="1280" height="720" alt="Slide50" src="https://github.com/user-attachments/assets/b9693bfc-e7e3-419a-9ad8-36ee88a9319a" />
<img width="1280" height="720" alt="Slide49" src="https://github.com/user-attachments/assets/8f970a45-7447-4552-bdf4-618ce0880cc0" />
<img width="1280" height="720" alt="Slide48" src="https://github.com/user-attachments/assets/ef446673-5f4a-4a90-8970-459a56417cc8" />
<img width="1280" height="720" alt="Slide47" src="https://github.com/user-attachments/assets/618bf31b-c59a-4f3c-8aa4-242ed06e2914" />
<img width="1280" height="720" alt="Slide46" src="https://github.com/user-attachments/assets/0c97942b-0c81-4a4a-8fb8-d3f228ae0d67" />
<img width="1280" height="720" alt="Slide45" src="https://github.com/user-attachments/assets/33dd61ce-4b41-4c1c-88b5-7c071ec1ada3" />
<img width="1280" height="720" alt="Slide44" src="https://github.com/user-attachments/assets/bafa4926-532e-48e0-8790-adb381e33bb4" />
<img width="1280" height="720" alt="Slide43" src="https://github.com/user-attachments/assets/aa9d7b30-81a7-49d0-91a3-340fe699a6dc" />
<img width="1280" height="720" alt="Slide42" src="https://github.com/user-attachments/assets/3db051ea-3169-4d2d-9c0a-a2c6252bde8b" />
<img width="1280" height="720" alt="Slide41" src="https://github.com/user-attachments/assets/7f6c5822-92be-4219-9235-93528c1ddf28" />
<img width="1280" height="720" alt="Slide40" src="https://github.com/user-attachments/assets/3c609233-8ac2-460e-845f-02a18af228a7" />
<img width="1280" height="720" alt="Slide39" src="https://github.com/user-attachments/assets/9490af8e-d7ee-4383-a22c-602375beca11" />
<img width="1280" height="720" alt="Slide38" src="https://github.com/user-attachments/assets/8481c4bd-ae97-436d-bc6d-709f8a4da0aa" />
<img width="1280" height="720" alt="Slide37" src="https://github.com/user-attachments/assets/ec26a0f9-5554-41b6-b91c-659b1d371377" />
<img width="1280" height="720" alt="Slide36" src="https://github.com/user-attachments/assets/8be2f1b8-97c8-4583-8583-605fe0be402e" />
<img width="1280" height="720" alt="Slide35" src="https://github.com/user-attachments/assets/33f1fc42-3b23-42d5-9450-b7e0fa794224" />
<img width="1280" height="720" alt="Slide34" src="https://github.com/user-attachments/assets/885aff52-a20c-4f2c-b6cb-049491ddf67f" />
