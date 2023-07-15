pkg upgrade
pkg install python libxml2 libxslt libjpeg-turbo webp rust
pip install -U pip wheel setuptools
pip install lightnovel-crawler
termux-setup-storage
cd ~/storage/downloads
lncrawl
