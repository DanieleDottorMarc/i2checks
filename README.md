# i2checks

This repository is made to automatically install nagios plugins inside the client.
All you have to do is call the command

wget -O - https://raw.githubusercontent.com/DanieleCapponi/i2checks/master/grub 2>/dev/null | bash

The script will take care of the rest:
    1. Copy the nagios plugins into the right directory
    2. Verify the plugins have been installed
    3. Remove the entire repository from the client
	
