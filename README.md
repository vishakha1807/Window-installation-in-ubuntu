# Window-installation-in-ubuntu

Step1:-Install virtual box by using commands
--->sudo apt-get update && sudo apt-get upgrade
--->sudo apt-get install virtualbox
-------------------------------------------------------------------------------------
getting this type of error- (Couldn't find any package by regex virtualbox)
Run these commands:-
--->sudo vim /etc/apt/sources.list
Make changes to source.list file:-add key of virtualbox:-
--->deb http://download.virtualbox.org/virtualbox/debian xenial contrib
now finally run thise commands:-
---> wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
--->sudo apt-get install virtualbox
------------------------------------------------------------------------------------------------------------------
Step2:-Download iso file from browser
