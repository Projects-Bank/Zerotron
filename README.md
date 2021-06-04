# Zerotron
Admin bot for the Project Zero Discord community

Make sure you have Python and the discord.py library installed.

# Prerequisites
discord.py works with Python 3.5.3 or higher. Support for earlier versions of Python is not provided. Python 2.7 or lower is not supported. Python 3.4 or lower is not supported due to one of the dependencies (aiohttp) not supporting Python 3.4.

# Installing

## You can get the library directly from PyPI:
python3 -m pip install -U discord.py

## If you are using Windows, then the following should be used instead:
py -3 -m pip install -U discord.py

## To get voice support, you should use discord.py[voice] instead of discord.py, e.g.
python3 -m pip install -U discord.py[voice]

### On Linux environments, installing voice requires getting the following dependencies:
libffi
libnacl
python3-dev

### For a Debian-based system, the following command will get these dependencies:
$ apt install libffi-dev libnacl-dev python3-dev
