# 4chan-reply-grabber (ch4rab) 🖼️
A simple tool to download the selected reply as an image from 4chan. 

Requires `selenium` with [Chrome WebDriver](https://chromedriver.chromium.org/downloads). Download the appropriate version with your installed browser and either place somewhere in `PATH` or root directory of the program.

```
pip install -r requirements.txt
./ch4rab.py
```
![](extras/screenshot.png)

#### Result:
![](extras/result.png)

#### How-to:
![](extras/how-to.png)


#### Bundle from source
```
pyinstaller --noconfirm --onefile --windowed --icon=icon.ico --add-binary "C:/bin/chromedriver.exe;./chromedriver.exe" ch4rab.py
```
