# jjwxc-downloader
A Python script to download free chapters of a novel from jjwxc in the txt format. It is used for educational purposes only. Please do not use it for commercial purposes.

## Prerequisite
- Google Chrome
- ChromeDriver (same version as Google Chrome)

You may check the version of Google Chrome in the Settings.

![version_of_google_chrome](check-chrome-version.png)

Download the correct ChromeDriver at https://chromedriver.chromium.org/downloads/version-selection. Additionally, you can check for the latest version of ChromeDriver at https://googlechromelabs.github.io/chrome-for-testing.

After downloading the zip file for ChromeDriver, unzip it and place the chromedriver executable in the same folder as the jjwxc-downloader script.
```plaintext
jjwxc-downloader/
├─ jjwxc.py
├─ chromedriver
```

## How to run
1. Install the dependencies
```plaintext
pip3 install -r requirements.txt
```
2. Run 
```plaintext
python3 jjwxc.py
```
3. Enter the novelid you want to download
   
   You can find novelid in the url of the novel. 

## Note
Each chapter name begins with ##. This is for later convenience, such as adding indexes when converting the txt to epub.

## Future work
1. Add conversion from txt to epub
2. Add GUI for editing metadata of the epub

Please add issue if you need any assistance.