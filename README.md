# Face-Mask-Detection-And-Social-Distancing-Monitoring
This is a project to prevent the spread of COVID-19 virus. This project is divided into  two parts. Face mask detection using image-net, Social distancing detection using YOLO v3 and numpy, matplotlib, etc. 






Explaination on how the model is working and how it can be used, in an organisation, the ppt is given as ->https://docs.google.com/presentation/d/1AY1qoEzO_MVPBAUz3oQPUNwaUtuqR4UrYGz5-_EYe3g/edit?usp=sharing



*pro tip- download the document in ppt format in order to see all the transitions for better understandings.


# How to Run it on your CPU (For Windows Users)
* Firstly download all the files from this repository.
* Then Download the All the files from this link.


https://drive.google.com/drive/folders/1ipHauXF92xLvv3Ghi9afquJlhg9l85np?usp=sharing

* Save all the filess in each folder inside the folder of the same name from the repository.
* Then download Anaconda for Windows.
* After installing open Anaconda prompt

# For Executing The Face Mask Detection Program
* Open the path of the face mask detection folder in the anaconda prompt
* Give this command 'pip install -r requirements.txt'
* Let it install all the required packeges
* After that is done  give the command 'python detect_mask_video.py'
* Wait for some time as it will process the whole mask detection code.
* Enjoy output if your webcam is working properly.

# For Social Distancing program
* Open the path of the social distancing detection folder in the anaconda prompt.
* Now we have to create a python vertual environment in order to execute this code.
* So give the command, 'pip install virtualenv' this will install the virtual environment.
* After installing we have to launch a vertual environment, with any name you like.
* Give the command 'virtualenv "any name you like"' (Eg:- env)
* Then we have to activate the vertual environment.
* Give the command 'env\Scripts\activate' or any vertual environment name you have given.
* Like the last program now install all the requird packeges use the command 'pip install -r requirements.txt'.
* Wait for all the packeges to get installed, and while waiting,
* Download any small video from the internet where people are walking on road or signal and save it in the file where the code is there with the name 'test.mp4'.
* Finally go to the Anaconda Prompt and execute this command, 'time python social_distance_detector.py --input test.mp4 --output results.avi --display 1'
* Wait for hours to process the data to give you output.
* Finally your output will be saved in an .avi file as 'results.avi' in the same folder which you can play and enjoy.






Hopefully everyone got the output. For any issues submit your problems in the issues section of the project.
