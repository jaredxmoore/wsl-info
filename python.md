# Necessary items to get python working

For Debian and Ubuntu, the following command will ensure that the required dependencies are installed:

sudo apt-get install build-essential libssl-dev libffi-dev python-dev

For Fedora and RHEL-derivatives, the following command will ensure that the required dependencies are installed:

sudo yum install gcc libffi-devel python-devel openssl-devel

## Things to install
* http://timmyreilly.azurewebsites.net/python-with-ubuntu-on-windows/
* https://pypi.org/project/virtualenv/
```
pip install virtualenv
```
* https://virtualenvwrapper.readthedocs.io/en/latest/
```
$ pip install virtualenvwrapper`
...
$ export WORKON_HOME=~/Envs
$ mkdir -p $WORKON_HOME
$ source /usr/local/bin/virtualenvwrapper.sh
$ mkvirtualenv env1
```
