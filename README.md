# QR Scanner Database

The code in this repository allows you to scan a qr code and send it to an excel database

## Setup
### Setting up the Computer Python Script
1. Clone the repository
'''
git clone https://github.com/knoah77/QR-Scanner-Database.git
'''
2. Install Python 3.8 [link](https://www.python.org/downloads/release/python-380/)
3. Create a Venv file [link](https://ordinarycoders.com/blog/article/python-virtual-environment)
4. Install the python packages using the requirements.txt file in venv
'''
pip install -r requirments.txt
'''
5. Setup for your computer is complete follow the steps below to complete the phone app installation


### Setting up the phone app
1. in your browser on your phone go to this repository and download the Phone-app.apk
2. Once the app downloads click on the downloaded file to install the app

## Using the app
1. using a ide of your computer run the python script
2. on your phone open the app
3. Click the scan qr code button in the app
4. Scan a qr code that has the following information in it (id,item name,location) Ex: 1234,box of stuff,lobby
5. After you scan it click the send button
6. the database will automatically be created or updated depending on if it is created or not

## Things that need to be changed in app and code for the code to work
1. IP
2. Port

## ToDO
- [ ] Add add input boxes to change ip and port in the app
- [ ] Update the user interface to look better
- [ ] add status updates
- [ ] add ip and port switch ability to the python script
- [ ] add ability to change the information before it is populated to the database (app or database)
- [ ] Generate a QR code for the updated information if above is completed




