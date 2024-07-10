<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

## General info
The primary goal of this project is to fine-tune a pre-trained Faster R-CNN model using the VOC dataset and deploy the model using Streamlit to create a user-friendly web application for image component detection.
	
## Setup
### Setup enviroment
First, you need to install Streamlit and the required libraries. You can do this using pip:
```
pip install streamlit
pip install torch torchvision
pip install pillow
pip install transformers
```
### Create the Streamlit App
download and install the code attached to the repo
### Running the Application
#### to run localy:
Save the script as app.py and run the Streamlit app using:
```
streamlit run app.py
```
#### to run on jupyter online:
create local tunnel
```
!npm install localtunnel
import urllib
print("Password/Enpoint IP for localtunnel is:",urllib.request.urlopen('https://ipv4.icanhazip.com').read().decode('utf8').strip("\n"))
!streamlit run app.py &>/content/logs.txt &
!npx localtunnel --port 8501
```
copy the password printed then use it to login to tunnel 
