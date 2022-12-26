This script creates a socket for each port and attempts to connect to it. If the connection is successful, the port is considered to be open. Note that this process may take a while, as the script needs to try to connect to every port from 1 to 65535.

You can modify the script to scan a different range of ports or a different host by changing the arguments passed to s.connect_ex(). For example, to scan a different host, you can replace 'localhost' with the IP address or hostname of the target host.

I hope this helps! Let me know if you have any questions.
