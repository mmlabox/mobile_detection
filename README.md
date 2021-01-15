# Mobile detection based on alwaysAI platform
alwaysAI is an essential computer vision development platform for creating and deploying machine learning applications on edge devices such as Raspberry Pi and NVIDIA Jetson Nano to name a few

## Setup
Start by creating an alwaysAI account by [clicking here](https://alwaysai.co/auth?register=true) or visit https://alwaysai.co to learn more. Once you have created you acount you will need to install alwaysAI CLI, you can do this by [cklicking here](https://alwaysai.co/docs/get_started/development_computer_setup.html). Next step is to setup you Raspberry PI to run you alwaysAI application, follow the instuctions [here](https://alwaysai.co/docs/reference/raspberry_pi_setup.html).

## Deploy and Run you application
Start by navigating to your application folder through the terminal

#### Run the following command to configure your application to run on Raspberry PI or your local computer
```bash
aai app configure 
```
#### Run the following command to deploy (run) the application
```bash
aai app deploy 
```
P.S. you will need to run this command every time you change anything in you code

#### Run the following command to start the application
```bash
aai app start 
```
you are now able to view till live video stream from your camera by visiting http://localhost:5000

## Close application
To close you application press CTRL C.


