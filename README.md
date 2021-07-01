**Mycroft Web Client**
===================

For Mycroft with new API (https://home.mycroft.ai) 

ex: cd ~/git/
    git clone https://github.com/vvstubbs/Mycroft-Web-Client
    cd Mycroft-Web-Client


How to install
-------------
Step 1  Download this repo to your download folder

    cd ~/mycroft-core/mycroft/messagebus/service

    Rename main.py main_ORG.py 	(Rename original main.py for backup)
ex: mv __main__.py main __main__ORG.py

    copy into "~/mycroft-core/mycroft/messagebus/service" all files and directory downloaded on Step 1
ex: cp -R ~/git/Mycroft-Web-Client/* ~/mycroft-core/mycroft/messagebus/service

Step 2	Restar Mycroft

    ./start.sh service
    ./start.sh skills
    ./start.sh voice


Setp 3
    Open you browser on http://MYCROFT_IP_ADRESS:8181/   (Not localhost) 


**Enjoy !**
--------

