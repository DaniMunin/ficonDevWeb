![Main Page](doc/MainPage.jpg)


![Admin Site](doc/AdminExample.jpg)

Installation
------------

In order to execute the application you need the following software and libraries:

    Requirements:
        - Python 2.7
        - Pymongo
        - Flask
        - MongoDB (v 2.4.1)
        - pip

You can install pip with: 

    easy_install python-pip

Once you have pip you can install Pymongo and Flask by executing the next command in doc folder: 
    
   pip install -r requirements.txt 
   

Once you have that and MongoDB, you can initiate the DB with some test data by executing the script in sql folder.

To run the server just execute the next command in src folder: 

    python server.py


And you're ready to go.

The application runs in port 9001.

The Admin site in localhost:9001/admin.html and the main site in localhost:9001/index.html



