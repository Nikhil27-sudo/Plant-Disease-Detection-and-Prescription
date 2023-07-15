# Plant-Disease-Detection-and-Prescription 

### This project is submitted for Deloitte's TechnoUtsav 3.0 TechE.

This whole project is implemented in IBM Cloud. Developed a Telegram bot that can predict
the disease from images of damaged plant leaves using Watson Visual Recognition. The bot will
then successfully explain the treatments to the user using Watson Assistant. The bot also uses the
"Language Translator," which is used to convert between the user's native language and English for
effective communication. "Text to Speech," and "Speech to Text" services are also used. Integrated
all the services using "Node-Red".

## Problem Statement
Plant diseases and pests pose a significant threat to crop yield and food supply. The lack of early disease recognition leads to widespread disease spread, exacerbating the global challenge of increasing agricultural production to feed a growing population. To address this, our solution leverages artificial neural networks. This model helps in identifying the diseases from which crops are suffering and suggests the best possible solution(remedies) to get rid of the disease.

This solution offers fast processing and accurate disease classification by analyzing input images. While currently recognizing specific plant diseases, our ongoing research aims to develop a universal plant disease recognition model for identifying general leaf abnormalities. Additionally, we have created a chatbot accessible via 'Telegram' that provides remedies for identified diseases. Users can upload images of affected leaves to receive comprehensive information on the disease, symptoms, causes, and management strategies. Alternatively, they can request targeted remedies by specifying the plant and disease names.

## Technical Architecture
<p align="center"> 
  <img src="https://github.com/Nikhil27-sudo/Plant-Disease-Detection-and-Prescription/blob/master/Technical%20Architecture.png" width="600" height="400">
</p>


Our solution architecture consists of the integration of the following IBM Watson services and TELEGRAM with NODE RED,
- Visual Recognition Service
- Watson Assistant Service
- Language Translator Service
- Text-to-Speech Service
- Speech-to-Text Service

## Flow Diagram

<p align="center"> 
  <img src="https://github.com/Nikhil27-sudo/Plant-Disease-Detection-and-Prescription/blob/master/Flow%20Diagram.png" width="800" height="400">
</p>

## Data Model

<p align="center"> 
  <img src="https://github.com/Nikhil27-sudo/Plant-Disease-Detection-and-Prescription/blob/master/Data%20Model.png" width="950" height="250">
</p>

## Demo

<p> 
  <img src="https://github.com/Nikhil27-sudo/Plant-Disease-Detection-and-Prescription/blob/master/Results3.png" width="400" height="600" align="left">
  <img src="https://github.com/Nikhil27-sudo/Plant-Disease-Detection-and-Prescription/blob/master/Results4.png" width="400" height="550" align="right">
</p>




