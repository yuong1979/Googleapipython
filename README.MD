#connecting google sheets api with python

based on a tutorial https://www.youtube.com/watch?v=4ssigWmExak

Clone the project

Cd into the project

Run source bin/activate to activate the virtual environment 

Go to google cloud to create a service account and create a new pair of keys and download the keys

Save the keys as keys.json in the main folder of the project as keys.json

Go to the google sheets you need in your project copy the url to SAMPLE_SPREADSHEET_ID in read.py

On google sheets share access with the service account that you have created.

Run python3 read.py








