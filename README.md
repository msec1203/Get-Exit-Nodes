# get_exit_addr.py

I came up with thie script after seeing a tweet @QW5kcmV3, regarding collecting and adding Tor exit nodes to lists of known bad IP addresses.

The script will take in the URL for the most up to date Tor exit nodes, and save the output to a local HTML file. 
The HTML file will then be read and all IP addresses will be extracted and placed in a .txt file which should make importing into a SIEM relatively easy.

I hope to update this script as I have time.
