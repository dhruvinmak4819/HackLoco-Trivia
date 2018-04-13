# HackQ-Trivia
Yet another HQ trivia bot, in Python. Automatically scrapes HQ Trivia questions without OCR and answers them.
# Currently in development, not functioning
## Getting Started
Requires Python 3.6+
### Dependencies
#### Required
```
aiohttp
bs4
nltk
unidecode
```
#### Optional
```
aiodns
cchardet
```
### Installation
```
git clone https://github.com/Exaphis/HackLoco-Trivia.git
cd HackLoco-Trivia
pip install -r requirements.txt
```

If on Mac, run: 
```
/Applications/"Python 3.6"/"Install Certificates.command"
```

In Python 3, run:
```
import nltk
nltk.download("all")
```
Enter your bearer token and device ID in the conn_settings.txt file. These values can be found by sniffing the traffic on your phone. The bearer token should be one line, without the word Bearer.

### Usage
```
python3 loco_main.py
```
