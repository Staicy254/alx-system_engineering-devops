
Network Concepts:
1. localhost/127.0.0.1:

Refers to the same entity.
localhost: A hostname that points back to the device itself.
127.0.0.1: The reserved loopback IP address associated with localhost.
Both are used to access services running on your own device without needing its external IP address.
2. 0.0.0.0:

In server applications:
Often used to listen for incoming connections on all available network interfaces of the machine.
Essentially tells the server to accept connections from any IP address bound to the machine.
In routing:
May represent a default route, meaning it points to the "gateway" used to reach devices outside the local network.
3. /etc/hosts:

A system file on Unix-based systems.
Stores a mapping of hostnames to IP addresses, allowing for custom hostname resolutions.
Often used to define local hostnames and their corresponding IP addresses for easy access within the system.
4. Displaying Active Network Interfaces:

The specific command varies depending on your operating system:
Linux/macOS: ip addr or ifconfig
Windows: ipconfig in Command Prompt or PowerShell
These commands list the network interfaces on your machine, including their names, IP addresses, and other relevant information.
