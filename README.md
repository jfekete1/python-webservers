# python-webservers
This repository provides usefull scripts to create python webservers for file upload and download.

# usage
if you have python 2.x installed, then use:
python2 simpleHTTP2.py 8080

if you have python 3.x installed, then use:
python3 simpleHTTP3.py

To Download a file from your webserver use: 
curl -O http://<server-IP>:9999/<FILENAME>

To Upload a file back to your webserver use: 
curl -F 'file=@<FILENAME>' http://<server-IP>:9999/
