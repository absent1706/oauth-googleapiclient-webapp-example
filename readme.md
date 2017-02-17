# Oauth2 (webapp workflow) example using Google API Client
Taken from https://developers.google.com/api-client-library/python/auth/web-app

## Setup

1. Set up API credentials:
   You can use ready-to-go `client_secrets.json` in project root.
   
   To setup from scratch:
   
   * Follow [these instructions](https://developers.google.com/api-client-library/python/auth/web-app) 
     to obtain `client_secrets.json`. 
     
     You should get `client_secrets.json` from here http://www.qopy.me/TGzHH_z4Qu-4u-SjqGaZ9Q
     
     Copy it to project root when you get it
     
   * Enable Google Drive API: http://www.qopy.me/l2n6Me2eRee8zy1UvSDMPg , http://www.qopy.me/Hi1ZN0AxSHCjAWoftIOVyA

 
2. open CMD, go to project root and type (Windows) 
```
virtualenv env
env\Scripts\activate.bat

pip install -r requirements.txt
```

3. Then run app:
```
python app.py
```