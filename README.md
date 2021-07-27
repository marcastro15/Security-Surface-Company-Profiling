# Security-Surface-Company-Profiling

Introduction:
-------------
There are different phases of "Cyber Kill" called Cyber Kill Chain framework developed by Lockheed Martin. As you all know, phases such as reconnaissance, weaponization, delivery, exploitation, installation, command & control, and actions on objective. Developing all these phases takes massive undertaking that require many developers' attempt. For this project, we will start with self "Reconnaisance" where we will profile the visitor's or company's website and their servers. This is likened private investigation (PI) on indivdual to see the initial assessment of what they are capable of. In this case, we would profile company's specific website. 

Profiling Features
------------------
- Network Scan
- Web URL Scan
- Web Contents Scan (mining)

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
- pip3 install pytest
- pip3 install numpy
- pip3 install matplotlib (plotting)
    + Test Installation in the command line. The file is included in this tutorial
        - ./test_mathplot_installation.py
- pip3 install pyx (graphs)

Note: This program is tested in Ubuntu environment using python 3 version. "pip3" command will install the library within the python 3's domain.

Running
-------


Future Development
-------------------
