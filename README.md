This installatino is tested on Ubuntu 18.04 LTS

How do I install?
update your ubuntu first, then install panel

sudo apt-get update && sudo apt-get upgrade -y;
sudo apt-get install libxslt1-dev libcurl3 libgeoip-dev python -y ;
rm install.py; wget https://bitbucket.org/emre1393/xtreamui_mirror/downloads/install.py;
sudo python install.py
If you want a whole NEW installation, choose MAIN.

If you want to install load balance on additional servers, add a server to panel in manage servers page, then run script and proceed with LB option.

If you want to update admin panel, select UPDATE, then paste download link of release_xyz.zip file.
