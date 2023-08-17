# Salesforce Einstein Vision API
## Introduction
This is an AI-Powered SFDC app, that can search record from images using Einstein Vision OCR model. The app is designed to optimize record searching and retrieval of diverse record type with minimal effort. The app is built on top of Salesforce Einstein Vision API and Salesforce Lightning Web Component.

## Features
- Search record from uploaded images
- Create record from OCR Data scanned uploaded images
- Identify Data Tag (e.g. Name, Address, Phone Number, etc.) from uploaded images

## Installation
### Prerequisites
- Salesforce Developer Edition
- Salesforce Einstein Vision API

### Steps
1. Clone the repository
2. Deploy the code to your Salesforce Developer Edition
3. Create a Lightning App Page
4. Add the Lightning Web Component to the Lightning App Page
5. Add the Lightning App Page to your Salesforce App

#### Special Note on JSON_Web_Token.Einstein_OCR_JWT.md-meta file
The file contains the RSA Key that is required to generate JWT token for Einstein Vision API. You will be needing you own RSA Key in order to To generate a new token. follow the steps below to get your own RSA Key:
1. Go to [Einstein Vision API Sign Up](https://api.einstein.ai/signup)
2. Click on Sign Up using Salesforce
3. Enter your Salesforce Developer Edition username and password
4. You will be redirected to a page where you will find your RSA Key. Copy the RSA Key and for safety measure download the einstein_platform.pem file by clicking download key button.
5. Copy the token and paste it in the JSON_Web_Token.Einstein_OCR_JWT.md-meta file in RSA_Key__c field
6. Subscriber__c field is your email address
7. Save / deploy the file


## Usage
### Search Record
1. Upload an image
2. Click the "SCAN" button
3. Click the "SEARCH Result" button to view data from org
4. Click the "Create Record" button to create new record
5. Click the "Clear" button to clear the image

### App Architecture

![App Architecture](https://i.imgur.com/YYojAKl.png)

### App Screenshots
![App Sceenshot 3](https://i.imgur.com/BHzRgUe.png)
![App Sceenshot 4](https://i.imgur.com/v2YbyPq.png)
![App Sceenshot 2](https://i.imgur.com/AqtXOQO.png)
![App Sceenshot 1](https://i.imgur.com/8ALL1Ds.png)


### App Demo

[Youtube Link : App Demo](https://youtu.be/TaFvjudaBj4)
