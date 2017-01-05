# GoogleVisionAutomationTools

get_images.py
-> This script takes in an application id as an input (Required) parameter and attempts to download and call the google vision api by way of the google_vision_tool.py and google_code.py scripts.

To run from the command line:
python get_images.py 9923fe97-48cb-45d7-b42c-deaeb2eb53b6

google_vision_tool.py
-> This script takes a set of images that are stored locally, builds a JSON payload that is compatible with the Google vision API, calls the API, and pushes the result of the request to a table that has already been defined on Robin.  

The dependencies are the following:  
Python 2  
psycopg2 (pip install psycopg2)  

