# PacktPub Video Downloader (pvdl)

The Easiest way to download any Packt video tutorial

**Notice: You need a Packt account with subscription or free trial to download videos**

## Features

* Download any video using your subscription
* Resume downloads
* Download rate limit
* Easy to use

## How to use

First you need to install the prerequisites. On Debian-based distributions run the following commands:

```bash
sudo apt update
sudo apt install build-essential libcurl4-openssl-dev libssl-dev
```

Clone this repository, install requirements and run the script. For example:

```bash
chmod +x ./pvdl.py
pip install --user -r requirements.txt

./pvdl.py -u username@example.com -p Passw0rd -l "https://subscription.packtpub.com/video/programming/9781788834995"
```

or install pvdl using pip:

```bash
pip install --user pvdl

pvdl -u username@example.com -p Passw0rd -l "https://subscription.packtpub.com/video/programming/9781788834995"
```

Usage:

```bash
usage: pvdl.py [-h] [-u USERNAME] [-p PASSWORD] [-r RATE_LIMIT] [-l LINK]

PacktPub Video Downloader

optional arguments:
  -h, --help            show this help message and exit

required arguments:
  -u USERNAME, --username USERNAME
                        Your Packt Username
  -p PASSWORD, --password PASSWORD
                        Your Password
  -r RATE_LIMIT, --rate-limit RATE_LIMIT
                        Download rate limit
  -l LINK, --link LINK  Packt Video link

```

## License

PacktPub Video Downloader is a free software and is licensed under GNU Public License v3+

For more information see [LICENSE](LICENSE)

## CUSTOM UPDATE

Run `make download` and will start to download this courses:


./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/web_development/9781838648558"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/web_development/9781839214332"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/programming/9781800200753"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/data/9781838640583"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/data/9781839212123"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/data/9781800566576"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/data/9781800209664"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/data/9781800202320"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/data/9781839219054"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/web_development/9781838555467"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/virtualization_and_cloud/9781789344738"
./pvdl.py -u EMAIL -p PASSWORD -l "https://subscription.packtpub.com/video/cloud_and_networking/97818010
