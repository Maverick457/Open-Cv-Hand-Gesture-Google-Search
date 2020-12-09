# Open-Cv-Hand-Gesture-Google-Search

Hand Gesture Recognition and Control using cv2

This project is developed using the concept and alogrithms of computer vision which is indeed recognised as the superset of image processing . In this we have developed a control system , where with just a sign of hand , we can google search and have results without any interation with hardware tools. The principal of our project is Human-Computer-Interation(HCI) domain of artificial intelligence.

Pre-requisite Libraries and language version supported

Python 3.6
Opencv 3.4.2
imutils
pyautogui
numpy
Installation (Ubuntu)


In this python 3.6 is a must because we are using PyAutoGui for vision hardware control and this library requires atleast 3.6 to work on.Therefore we recommend to use Pycharm as the integrated development environment for this.

  a. Steps to install Pycharm
  	1. Go to https://www.jetbrains.com/pycharm/download/#section=linux . Download the
  	community edition.
  	2. Open terminal
  	3. cd Downloads
  	4. tar -xzf pycharm-community-2020.1.tar.gz
  	5. cd pycharm-community-2020.1
  	6. cd bin
  	7. sh pycharm.sh
  	8. A window will open ,click on `do not import settings`
  	9. Set default options
  	10. Installed successfully
  b. Now download python 3.6 interpreter
  	1. go to https://www.python.org/downloads/


Create project in pycharm

  a. Create a new project
  b. import the python 3.6 interpreter as `base interpreter` option and let everything as it is.
  c. We got our own virtual environment .
  d. Go to file->settings
  e. in left hand column select `project` tab -> project interpreter
  f. Here we can see installed package , go to `+` sign on the right.
  g. Now we get the list of packages which we can install.
  h. Install all the libraries with specific version mentioned above.
  i. Now we have all the libraries installed.

Running the given project

  a. Go to file -> open -> select the required python file from destination where it is copied.
  b. the file gets opened
  c. right click on the file -> select run
  d. Program gets executed.

What to do after program gets executed

  a. It open ups the webcam , wait for the calibration (3 sec) .
  b. place your hand as ‘1’ into the rectangle. It will recognize the numbers as shown 0-5.
  c. whenever we show ‘4’ , the gesture control gets triggered , it open up the browser , triggers google voice search , user speak anything to search , search   gets completed.
  d. This control we have restricted for only working for once to improve gesture control mechanism.
  e. To make control again , re-run the program , show ‘4’ and search is excecuted.

Important pre-requisites and setup to run the project

  a. To avoid calibration issues with the contours as these are still sensitive , We recommend to
  have a clear background in front of webcam without any object.
  b. It takes around 3 secs to calibrate and adjust pixel frames. during this, webcam should be
  stable.
  c. Place your hand fully in the rectangle with fingers touching the top side of rectangle so as to
  detect full curvature of hand and finger and detect number accordingly.
  d. Have sufficient lighting for contours to easily grep around the hand . Insufficient lighting would
  result in inaccuracy.
