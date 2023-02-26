# Face-Detection-ML-Project-Python
To detect human face from a given image, detect a face from a live -webcam video and to create an attendance system using Web-cam Face Recognition.

Face detection -I used various libraries like OpenCv,matplotlib,Cascade Classifier,haarcascade_fronralface_default.xml,dlib,HOG,CNN,face_recognition etc to detect human face from a given image, detect a face from a live -webcam video and to create an attendance system using Web-cam Face Recognition.

Using cv2 and for loop:-

<img src="https://user-images.githubusercontent.com/84846378/221408133-70212b9b-f337-49fc-8b17-c222706265fa.png" width="50%" height="50%">

<img src="https://user-images.githubusercontent.com/84846378/221408749-4de84c49-17f0-4727-9b12-eb60482d87fb.png" width="50%" height="50%">

<img src="https://user-images.githubusercontent.com/84846378/221408995-63091916-1609-4078-8778-2874e00fb5f6.png" width="50%" height="50%">


Using CNN detector:-

<img src="https://user-images.githubusercontent.com/84846378/221408842-8345d8cc-c482-4347-b557-fd6c4422408f.png" width="50%" height="50%">

<img src="https://user-images.githubusercontent.com/84846378/221409105-54b0f964-a34d-4376-8182-bd293f054d69.png" width="50%" height="50%">


Using Haarcascade Detector:-

<img src="https://user-images.githubusercontent.com/84846378/221408898-e6622229-e898-4405-a1e2-77c7f7bba737.png" width="50%" height="50%">

<img src="https://user-images.githubusercontent.com/84846378/221409140-6c8cb58c-5b53-43ce-aca5-cca33f10ed96.png" width="50%" height="50%">


Using Histogram of Oriented Gradients:-

<img src="https://user-images.githubusercontent.com/84846378/221409209-97ed8612-ffdd-4db0-8ea6-8d0e08c639de.png" width="50%" height="50%">


Using Cascade Classifier:-

<img src="https://user-images.githubusercontent.com/84846378/221409346-6fd1902c-6b00-4267-ad45-2bb3964c34cd.png" width="50%" height="50%">


Full Body detection:-

<img src="https://user-images.githubusercontent.com/84846378/221408628-7a9c5575-c88d-4a4c-a375-0cf745787507.png" width="50%" height="50%">


# Comparison of accuracy and time to load of various classifiers 

1. CNN detector on family photo------all 6 faces detected with 100% accuracy----takes a bit time to load 

<img src="https://user-images.githubusercontent.com/84846378/221409663-19211c53-dfad-4b4f-8961-5bfd6e89dcd6.png" width="50%" height="50%">

2. dlib  on family photo------all 6 faces detected with 100% accuracy----fast loading

<img src="https://user-images.githubusercontent.com/84846378/221409806-f4737adc-b30a-4ab4-8bd8-542006063981.png" width="50%" height="50%">

3. HOG  on family photo------all 6 faces detected with 100% accuracy----medium speed loading

<img src="https://user-images.githubusercontent.com/84846378/221409871-9fc3c6d6-6812-47f9-9ef8-3ce2763aa921.png" width="50%" height="50%">

4. Cascade[face_detector.detectMultiScale] & for loop  on family photo------all 6 faces detected with 100% accuracy----fast loading, but scale factor has to be
adjusted by trial and error

<img src="https://user-images.githubusercontent.com/84846378/221409986-b748762b-96dc-470a-8686-1a8e8288e7f1.png" width="50%" height="50%">


Thus,best & easy to use libraries so far for face detection are 
#### cnn- 100 percent accurate but slow 
#### dlib- almost 100% accurate and fast


# Attendance Excel generated via live web cam:-

<img src="https://user-images.githubusercontent.com/84846378/221410104-0bce56ac-471d-4d58-abb8-35187ad4acf4.png" width="50%" height="50%">


### Continued development

I would like to learn futher advance techniques which will help my model to differentiate between an actual live person and an image/id-card of a person in Live web-cam Attendance system.


#### Author

LinkedIn - [Mihir Chavan](https://www.linkedin.com/in/mihir-chavan-643615234/)
Github - [@mihirc0111](https://github.com/mihirc0111)

#### Acknowledgments

I learned ML from acmegrade modules of Sir Noble Xavier.
