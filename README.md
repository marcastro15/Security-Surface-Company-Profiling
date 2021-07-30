# Security-Surface-Company-Profiling

Introduction:
-------------
There are different phases of "Cyber Kill" called Cyber Kill Chain framework developed by Lockheed Martin. As you all know, phases such as reconnaissance, weaponization, delivery, exploitation, installation, command & control, and actions on objective. Developing all these phases takes massive undertaking that require many developers' attempt. For this project, we will start with self "Reconnaisance" where we will profile the visitor's or company's website and their servers. This is likened private investigation (PI) on indivdual to see the initial assessment of what they are capable of. In this case, we would profile company's specific website. 

Profiling Features
------------------
- Network Scan (IP/Port) - map the network to find devices that are connected to the same network.
- Web URL Scan - (target website)
- Web Contents Scan (mining)
- Check for XSS (Cross Scripting)
- Note: This program needs elevated privilege to run.

Pre-requisite Modules/Installation
----------------------------------
- apt-get update (update source library)
- Python version 3
- Scapy 2.4.3-2.4.4
  + Install Latest Version 
      1. wget --trust-server-names https://github.com/secdev/scapy/archive/master.zip   
      2. unzip master
      3. cd scapy-master
      4. python3 setup.py install
- apt-get install tcpdump (command line tool packet analyzer)
- pip3 install scrapy
- pip3 install pytest (optional for testing only)
- pip3 install numpy
- pip3 install matplotlib (plotting)
    + Test Installation in the command line. The file is included in this tutorial
        - ./test_mathplot_installation.py
- pip3 install pyx (graphs)
- apt-get install python3-bs4
- For crawler
    -  pip3 install beautifulsoup4
    - apt-get install python-lxml
    - apt-get insall python-html5lib
- Network Port Scanner
    - pip3 install colorama

Note: This program is tested in Ubuntu environment using python 3 version. "pip3" command will install the library within the python 3's domain.

Running
-------

Acronyms and Definition
-----------------------
ARP - Address Resolution Protocol: A communication protocol used for discovering the link layer address, such as a MAC address, associated with a given internet layer address, typically an IPv4 address.

Future Development
-------------------
