// Create_ssh_connection.py

This code creates an SSH connection to a remote computer with the IP address 192.168.198.136. The user's username is ubuntu and their password is sulphr. The connection times out after 5 seconds. The paramiko library is used to handle the SSH connection. If the code is run, it will print the client object, which represents the SSH connection.

// Brutus.py


This code is a brute-force password cracking program. It uses the paramiko library to create an SSH connection to a remote computer with a given IP address. The program then generates all possible combinations of a given character set (charset) of a given length (length) and tries each combination as a password for the remote computer until the correct password is found. The timefunc decorator is used to time the execution of the crackit method. If the password is found, the method returns it, otherwise it returns None.
