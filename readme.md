**PAN Card Tampering Detection Project**

***Overview***

This project is a web application designed to detect tampering in PAN cards using image processing techniques. The application is built using Flask, a lightweight WSGI web application framework in Python, and is deployed on Heroku, a cloud platform that enables developers to build, run, and operate applications entirely in the cloud.

***Features***

.  Upload PAN Card Image: Users can upload an image of a PAN card for tampering detection.

.  Image Processing: The uploaded image is processed to check for any signs of tampering.

.  Result Display: The results of the tampering detection are displayed to the user.

.  User-Friendly Interface: A simple and intuitive web interface to interact with the application.


***Requirements***

Python 3.x

Flask

OpenCV

NumPy

Heroku CLI (for deployment)


***Step to run application:***

Step 1:	Create the copy of the project.

Step 2: Open command prompt and change your current path 
to folder where you can find 'app.py' file.

Step 3: Create environment by command given below-
conda create -name <environment name>

Step 4: Activate environment by command as follows-
conda activate <environment name>

Step 5: Use command below to install required dependencies-
python -m pip install -r requirements.txt

Step 6: Run application by command;
python app.py

You will get url copy it and paste in browser.

Step 7: You have sample_data folder where you can get images to test.
