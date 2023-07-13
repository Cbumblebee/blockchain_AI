# blockchain_AI

(You should have installed python, pip, and curl first)

Open cmd prompt and go to the path, where blockchain_try1.py is. 


Then, write: python blockchain_try1.py

on another cmd prompt, you write different cURL requests you need:
for the transaction:
  curl "http://127.0.0.1:5000/txion" -d "{\"from\": \"akjflw\", \"to\": \"fjlakdj\", \"amount\": 3}" -H "Content-Type: application/json"
for displaying all blocks:
  curl "http://127.0.0.1:5000/blocks"
for mining:
  curl "http://127.0.0.1:5000/mine"

in PowerShell, you might need to replace "curl" with: C:\Windows\System32\curl.exe

