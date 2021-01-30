# raspberry-pi-command List 
> python virtual env setup
`sudo apt-get install build-essential`

`sudo apt-get install libncurses5-dev libncursesw5-dev libreadline6-dev`

`sudo apt-get install python-dev`

`sudo apt-get install libssl-dev openssl`

`mkdir python-source`

`cd python-source/`

` wget https://www.python.org/ftp/python/3.9.1/Python-3.9.1.tgz`

`python3 --version`

`tar zxvf Python-3.9.1.tgz `

`ls -al`

`cd Python-3.9.1/`

`ls -al`

`./configure --prefix=/usr/local/opt/python-3.9.1`

`make`

`sudo make install`

`/usr/local/opt/python-3.9.1/bin/python3.9 --version`

> Setup the app python virtual environment
In *~/python-source/Python-3.9.1*

`sudo su`
 
`cd var`
 
`ls -al`
 
`mkdir www`

`cd www`

`mkdir lab_app`

`cd lap_app`

`/usr/local/opt/python-3.9.1/bin/python3.9 -m venv .`

`. bin/activate`

`python --version`

`deactivate`
