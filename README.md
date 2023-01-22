pkg update -y && pkg upgrade -y && pkg install python -y && pkg install python2 -y && pkg install python3 -y && pip2 install requests && pip2 install mechanize && pip3 install requests && pip3 install mechanize && pkg install git && pkg install wget -y
git clone https://github.com/lostdevill/adevil.git
cd devil && python2 devil.py
