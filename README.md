FILE NAME
360_seting_up_system_Python_notes.txt

1. WHAT IT DOES
This set of instructions will result in installing
Python 3.11 at the system level.

2. REQUIRES
EC2 Instance

3. ORIGINAL WORK
Raspberry Full stack 2018, Peter Dalmaris

4. HARDWARE
5. SOFTWARE
6. WARNING!
7. CREATED
Lo Bianco, 2023

8. TYPICAL OUTPUT
-
---------------------------------------------

Step 1
------
$ sudo apt-get update
$ sudo apt-get upgrade

Step 2
------
$ sudo apt-get install build-essential

Step 4
------
$ sudo apt-get install libncurses5-dev libncursesw5-dev libreadline6-dev libffi-dev

Step 5
------
$ sudo apt-get install libbz2-dev libexpat1-dev liblzma-dev zlib1g-dev libsqlite3-dev libgdbm-dev tk8.6-dev libssl-dev openssl
$ sudo apt-get install libboost-python-dev
$ sudo apt-get install libpulse-dev

Step 6
------
$ sudo apt-get install python-dev
$ sudo apt-get install vim

Step 7
------
$ cd ~
$ mkdir python-source
$ cd python-source/

Step 8
------
$ wget https://www.python.org/ftp/python/3.8.1/Python-3.8.1.tgz

Step 9
------
$ tar zxvf Python-3.8.1.tgz

Step 10
------
$ cd Python-3.8.1/
$ ./configure --prefix=/usr/local/opt/python-3.8.1

Step 11
-------
$ make

Step 12
-------
$ sudo make install

Step 13
-------
$ /usr/local/opt/python-3.8.1/bin/python3.8 --version

(The response should be: Python 3.8.1)