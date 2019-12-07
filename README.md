# youtube-comment-downloader
Simple script for downloading Youtube comments without using the Youtube API. The output is in line delimited JSON.

### Dependencies
* Python 3.6+
* requests
* lxml
* cssselect

The python packages can be installed with

```
pip3 install -r requirements.txt
```

### Usage
```
usage: downloader.py YOUTUBE_VIDEO_ID

Download Youtube comments without using the Youtube API

