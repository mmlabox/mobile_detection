# Mobile detection based on alwaysAI platform
alwaysAI is an essential computer vision development platform for creating and deploying machine learning applications on edge devices such as Raspberry Pi and NVIDIA Jetson Nano to name a few

## Setup
Start by creating an alwaysAI account by [clicking here](https://alwaysai.co/auth?register=true) or visit https://alwaysai.co/auth?register=true
Install alwaysAI CLI

Navigate to the folder containing the app through the Terminal

Run “aai app configure” and follow the Instructions for project configuration

Choose "Remote device" as a destination
If you already have a device configured choose "Use saved device" otherwise "Create new device" and follow the instructions
Run “aai app deploy” to deploy the app to your raspberry Pi. If any changes to the application has been made then this step must be repeated

Run “aai app start” to start the application

Open this link in your browser " http://localhost:5000 " to view the live video
