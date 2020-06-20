# NLP to identify mobile application set-up
This project has been conducted during a Special Problem course taken at Georgia Institute of Technology (Atlanta) in the COEUS laboratory. 
The purpose of this project is to identify from the user-manual whether the product require a automatic or manual set-up. 

## Step into the project
From the user manuals, understanding and interpreting the language to determine whether the 
application needs an automatic and manual set-up, using Topic Modelling NLP tasks.
For this part I decided to go over two tutorials on topic modelling on Python : 
https://towardsdatascience.com/topic-modelling-in-python-with-nltk-and-gensim-4ef03213cd21
https://stackabuse.com/python-for-nlp-topic-modeling/
Here is a description of my work : 
- Installation of jupyter notebook on anaconda for easy use
- Download of almost every manuals of the smarthome products in the lab : Belkin Wemo Link, Chinese Webcam and Google HomeHub are
missing at the moment (some of the PDF files found may be wrong : please check within NLP_Topic_Modelling/manuals_pdf/check
- Extracting the text of the PDF to create dictionaries for each PDF file
- Use of both gensim and sklearn libraries to model LDA and NMF natural language processing topic modelling methods

## Improve the project
The different parts can be found in the different notebooks, from the preprocessing, to the use of topic modelling methods.
Here are a few suggestions on how to improve this project : 
- Instead of using the full manuals, we may want to use only the part of the manuals about the installation/setup of the product
- Study the removed and kept words that are used to recognized the topic and edit the custom_lists during the preprocessing step

## Linked project : Appium scripting
The code won't appear on my github as the work done belongs to the laboratory's activity however here is a few information about the project : 
First, I developed a couple scripts with the software Appium, to be able to retrieve within each application, the 
firmware version associated with the devices used in the laboratory. My framework was the following : 
- IntelliJ : code editor for the script through Java coding
- Android Studio SDK : adb devices and SDK used to be able to communicate with external devices, 
such as a tablet or smartphone running on Android
- Appium : automation tool used to run a server that will be handling the request from the script, 
and monitor taps, touch, key entries in the application via the communication with the SDK