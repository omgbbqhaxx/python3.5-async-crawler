# python3.5-async-crawler [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/mehmetkose/python3.5-async-crawler/edit/master/README.md)
Python3.5 Async Crawler Example with aiohttp and asyncio


## Installation

### Installation Python 3.5

```bash
sudo add-apt-repository ppa:fkrull/deadsnakes
sudo apt-get update
sudo apt-get install python3.5
```
### In virtualenvwrapper

```bash
mkvirtualenv async_crawler --python=/usr/bin/python3.5
python async_crawler.py
```
## or

### Replace python3 with python3.5

```bash
sudo mv /usr/bin/python3 /usr/bin/python3-backup
sudo ln -s /usr/bin/python3.5 /usr/bin/python3

sudo apt-get install python3-pip
sudo pip3 install aiohttp
python3 async_crawler.py
```
