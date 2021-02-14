# Robot Framework Setup Guide

1. git clone https://github.com/chihangfu/robot_framework.git into C:\work\

2. Download Python 3.8.0

   https://www.python.org/downloads/release/python-380/

2. run command `python --version`  to confirm installation successfully

3. run command `python get-pip.py` 

4. run command `pip --version` to confirm installation successfully

5. run command `pip install robotframework`

6. run command `python -m robot --version` to confirm installation successfully

7. run command `pip install -U wxPython`

8. run command  `python -c "import wx;print(wx.__version__)"` to confirm installation successfully

9. run command `pip install robotframework-ride`

10. run command `pip install robotframework-selenium2library`

11. run command   `python -c "import Selenium2Library;print(Selenium2Library.__version__)"`

12. download the chromedriver version 88 
    https://chromedriver.storage.googleapis.com/index.html?path=88.0.4324.96/

13. unzip chromedriver.zip and copy the chromedriver.exe to python path

14. revise application.py , replace `self._initial_locale = wx.Locale(wx.LANGUAGE_ENGLISH)`

    to `locale = wx.Locale(wx.LANGUAGE_ENGLISH)`

15. run command `ride.py` to launch the Robot Framework IDE

16. click File -> open Directory -> load C:\work\robot_framework into RIDE

17. select the test class **Open Google** and click the Run tab at right panel, then click Start

19. wait the chrome prompt out and will show the message `chrome 目前受到自動測試軟體控制`





### References

1. https://www.coderbridge.com/series/1192363370c740e380a5437440013cd5/posts/8651d8458b6f4f538fbeb2cb330a933a
2. https://stackoverflow.com/questions/21444951/wxpython-3-0-breaks-older-apps-locale-error
3. https://stackoverflow.com/questions/61441937/robotframework-ride-not-opening