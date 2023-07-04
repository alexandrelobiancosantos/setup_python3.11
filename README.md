# FILE NAME
README.md

## 1. WHAT IT DOES
This set of instructions will setup the venv on AWS EC2 Instance.

## 2. REQUIRES
- Ubuntu 22.04 EC2 Instance

## 3. ORIGINAL WORK
Raspberry Full stack 2018, Peter Dalmaris

## 4. HARDWARE
- 

## 5. SOFTWARE
- 

## 6. WARNING!
- 

## 7. CREATED
- Lo Bianco, 2023

## 8. TYPICAL OUTPUT
- 

---

## Step 1
```shell
$ sudo apt-get update
$ sudo apt-get upgrade -y

## Step 2
$ sudo apt-get install build-essential -y
$ sudo apt-get install libncurses5-dev libncursesw5-dev libreadline6-dev libffi-dev -y
$ sudo apt-get install libbz2-dev libexpat1-dev liblzma-dev zlib1g-dev libsqlite3-dev libgdbm-dev tk8.6-dev libssl-dev openssl -y
$ sudo apt-get install libboost-python-dev -y
$ sudo apt-get install libpulse-dev -y
$ apt install python3.10-venv
