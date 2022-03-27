# Python Port_Scanner

A port scan is a technique for identifying which ports are open on a network. Port scanning is similar to knocking on doors to determine whether somebody is home because ports on a computer are where information is transferred and received.
A port scan on a network or server reveals which ports are open and listening (receiving data), as well as the presence of security measures like firewalls between the sender and the target. Fingerprinting is the term for this method. It's also useful for evaluating network security and the firewall's effectiveness.

The services provided by ports differ. They range in number from 0 to 65535, however some ranges are more commonly utilised.
The Internet Assigned Numbers Authority has assigned services to ports 0 through 1023, which are known as "well-known ports" or standard ports (IANA).

The following are some of the most well-known ports and the services they provide:

* File Transport Protocol (FTP) data transfer port 20 (udp).

* Secure Shell (SSH) protocol for secure logins, ftp, and port forwarding is available on port 22 (tcp).

* Telnet protocol for unencrypted text communications (port 23 (tcp)).

* Domain Name System (DNS) transforms names of all machines on the internet to IP addresses using port 53 (udp).

* World Wide Web HTTP port 80 (tcp)

Standard services are also available on ports following 1023, as well as ports that, if open, indicate an infected machine due to their popularity with some sophisticated Trojans and viruses.


## Instructions for Use:

- Clone the repository or download the contents of the repository as a Zip file.
- Set up Python on your computer
- Run the following command in your terminal to install the python packages listed in the requirments.txt file:

    ```python3
    >>> pip install -r requirements.txt #for windows
    >>> pip3 install -r requirements.txt #for macos and linux
    ```
 
- Run the port_scanner.py file by running <i>python port_scanner.py</i> or <i>port_scanner.py</i> on it.
- The user is then prompted to enter the IP address that he or she wishes to scan, which can be a domain or a direct address.
- The scanner will then scan all ports, which may take some time, and will inform us whether each port is open or closed.