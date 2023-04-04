# CyclEYE :recycle:

## 2023 GDSC Solution Challenge

### Team :school: : CyclEYE GDSC Hanyang, Seoul, Korea
MLDL :robot: : DongWoo Lee, Hanyang University, Dept.of Industrial Engineering,GDSC Hanyang, General Member

APP BACK-END :computer: : Dohyun Kim, Hanyang University, Dept.of Industrial Engineering

APP FRONT-END :iphone: : Soobeen Yim, Hanyang University, Dept.of Information System, GDSC Hanyang, General Member

### Google Techs Used :wrench: :
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=Keras&logoColor=white"/> <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=Kaggle&logoColor=white"/> 
<img src="https://img.shields.io/badge/Google Colab-F9AB00?style=flat-square&logo=Google Colab&logoColor=white"/> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/Google Cloud-4285F4?style=flat-square&logo=Google Cloud&logoColor=white"/> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/>
<img src="https://img.shields.io/badge/Android Studio-3DDC84?style=flat-square&logo=Android Studio&logoColor=white"/>

### UN Sustainable Development Goals :chart_with_upwards_trend:
<img width= "20%" src="https://user-images.githubusercontent.com/113010196/229691864-14b600bf-1f1a-4b10-910b-84089e49eb08.png"> <img width= "20%" src="https://user-images.githubusercontent.com/113010196/229692474-92db0ce0-f1e6-4d62-b09a-f6fe77144042.png">

### How CyclEYE Service was developed :mag_right:
In Korea, a survey was conducted on 1,000 men and women more than age 18 to see if they did not comply with the standards for separate discharge of recycled waste and food waste. More than 90 percent said they did not keep it properly. For that reason, the answer was that there was little knowledge about recycling, so it was annoying, and it was unclear where to throw it away. People often throw away ambiguous items like ice packs or bubble wrap because they don't know how to separate them or because they don't know how to throw them away, such as dirty beverage bottles. In the end, this lack of knowledge and interest in recycling will only promote environmental pollution. In order to prevent such environmental pollution and create a better world, we decided to develop a mobile application that provides guidelines on how to separate and collect photos. Through this service, many people will gain basic knowledge of recycling and make it possible to separate ambiguous garbage well. Therefore, it will reduce waste through properly discarded waste. Our first goal is to have a clean natural environment and less abnormal weather than before, so many people live happily in a good environment.

## Moblie App 'cyclEYE' :recycle:

### 1. START  :calling:
<img width="400" alt="readme1" src="https://user-images.githubusercontent.com/113010196/229709414-13cc5732-c6da-414d-ae58-9f46bd65cfcf.png">
This is the first start screen of the application we made. The service name was written above, and an image related to the cycle was inserted. In addition, if you press the start! button, you can start Cyclie's service in earnest. 

&nbsp;

### 2. THREE EVENTS OF cyclEYE :memo:
<img width="400" alt="readme2" src="https://user-images.githubusercontent.com/113010196/229710235-e1d4c9bf-48bc-4be3-abcd-f2282baa35c8.png">
We developed it so that you can do three events by pressing the start button. First of all, photo. If you press this, you can take pictures of trash that you are curious about how to recycle using the camera application and receive guidelines. The second is the explain. In addition to the guidelines, it notes ways to dispose of representative recycling items appropriately in general. The third is the previous record. This is useful when users want to throw away the same trash later, but they forget. If you click on the previous record, the trash you took in the past and the guidelines for it are written, so you can separate it by referring to the records.

&nbsp;

### 3. PHOTO :camera:
<img width="400" alt="readme3" src="https://user-images.githubusercontent.com/113010196/229797163-2ec3d72e-101a-425c-9988-5c232a1b2785.png">
The photo function is the main function of this application. First, prepare garbage that I don't know how to recycle. Then scan with the app's camera. The camera is authorized, so if you touch no, you cannot take a picture. And you can take a picture. If you don't want to use it, you can take it again until you want. And if you take a picture that you like, press the check button and the model we prepared recognizes the trash. So the results window tells you whether it can be recycled or not and where to throw it away. It is also given detailed guidelines on how to dispose of it, making it more convenient, accurate, and the best way to dispose of garbage and protect the natural environment. In the case of ambiguous garbage, we also prepared a model with special guidelines for it. For example, in Korea, you cannot immediately throw away a bottle of water that is labeled. Labels should be discharged in plastic, and unlabeled water bottles should be discharged in plastic. Therefore, if a user scans a labeled water bottle on a camera, a result window appears that the separation is ambiguous. And guidelines are given on how to throw it away correctly. In this way, a model was prepared so that users could obtain more convenient and accurate separation and collection knowledge.

&nbsp;

### 4. GUIDELINES OF SEPERATE GARBAGE  :put_litter_in_its_place:
<img width="400" alt="readme4" src="https://user-images.githubusercontent.com/113010196/229805484-09218523-bdc0-4e89-89a1-2908ff408578.png">
It contains a basic explanation of how to throw away trash when you press explain. Since our model is classified into a total of 12 types, it contains guidelines for recycling of 12 types. It also tells you how to separate and collect ambiguous garbage, but I thought it would be good to tell you the most basic garbage separation method, so I inserted this function. Therefore, if the user wants to see the recycling method for glass, press the glass button. Then comes the basic recycling method for glass.

&nbsp;

### 5. PREVIOUS RECORD  :open_file_folder:
<img width="400" alt="readme5" src="https://user-images.githubusercontent.com/113010196/229807340-84831f21-e679-41e1-8ae7-ba22869c53ec.png">
Finally, if users press the previous record button, it contains the pictures we have taken so far and guidelines on how to separate them. The reason why this function was implemented is that it would be good for users to remember the exact method of separating and collecting waste they took. First of all, users will definitely scan trash with cameras that they don't know how to throw it away. And you'll have to learn a few times to fully recognize it. Therefore, they developed it so that they can see four trash pictures they took before. Then users will now recognize the recycling method and share knowledge with others to create a cleaner environment and no abnormal weather will occur.


