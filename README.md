Object-Counting-Flutter-App
An Object Counting application built using Flutter, NGROK, Flask, using the YOLOv8 model from the ultralytics library.

Getting Started
Clone this github repo to your local system and navigate to the API folder.

Setting Up a Virtual Environment and Installing Libraries
Install virtualenv (if not already installed)
pip install venv
Create a Virtual Environment
python3 -m venv myenv
Activate the virtual environment by running the appropriate command for your OS
source myenv/bin/activate
Once activated, install the requored libraries from the requirements.txt file
pip install -r requirements.txt
Get started with the server side
Get the flask API endpoint running on your localhost
python3 main.py
Install NGROK on your system
sudo apt install NGROK
Run the below line to create a HTTP tunnel
ngrok http 4000
Use the link obtained from above and paste it in the main.dart file on line 49

Move back to the original directory, Run your flutter project (assuming flutter is installed)

flutter run
All credits to the YOLOv8 creators for the pretrained yolov8 model. Find their Github @ https://github.com/ultralytics/ultralytics
