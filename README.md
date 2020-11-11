# checkMyPass
This project is a small Python script that uses the Have I Been Pwned API for safely checking whether a password has been pwned, without sharing it, or its hash. Instead, it sends the first 5 characters of the hash and the API sends back all hashes that start that way. This script then checks whether your hash is in the response.

#Usage
Before running the script, download the requests Python module by going into CMD and typing pip install requests
Use the script by calling it with your password in plaintext python checkMyPass.py password 
	   
