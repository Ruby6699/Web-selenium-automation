# selenium operates the browser
## import selenium
```
from selenium import webdriver

import time
```
## start the browser
```
driver = webdriver.Chrome()
```
## open the Web page
```
driver.get("https://www.google.com.au/")
```
## 5 seconds rest
```
time.sleep(5)
```
## maximize window
```
driver.maximize_window()
```
## minimize window
```
driver.minimize_window()
```
## quit browser
```
driver.quit()
```
## Return to previous page
```
driver.back()
```
## go to next page
```
driver.forward()
```
## refresh page
```
driver.refresh()
```
## Screenshot of the page
```
driver.save_screenshot('page.png')
```
## Get the title of the page
```
title = driver.title
print(title)
```
## Get the source code of the page
```
html = driver.page_source
print(html)
```
## Get the handle of the current page
```
win = driver.current_window_handle
print(win)
```
## Get a handle of all open windows
```
wins = driver.window_handles
print(wins)
```
## Get the url of the current page
```
url = driver.current_url
print(url)
```
