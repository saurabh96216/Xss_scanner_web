# Xss_scanner_web
Simple xss scanner

# Installation:
Type the following in the terminal.

git clone https://github.com/faizann24/XssPy/ /opt/xsspy

The tool works on Python 2.7 and you should have mechanize installed. If mechanize is not installed, type "pip install mechanize" in the terminal.

You will also need the mechanize distribution, you can install it with pip: pip install mechanize

# Usage:
python XssPy.py website.com (Do not write www.website.com OR http://www.website.com)

# Docker
Advantage of Docker is that is will run on every machine. You don't need to install Pip packages or use a Venv. Package versions are pinned. This ensures that XssPy will also run in the future. Regardless which Python-Version you've running on you machine.

Docker build
docker build -t xsspy .
Docker usage
After you build

docker run -t xsspy -u website.com
Payloads
# If you have found a XSS vulnerability, you can try the payloads.
