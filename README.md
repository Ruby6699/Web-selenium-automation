# selenium operates the browser
```
from selenium import webdriver

import time

driver = webdriver.Chrome()

driver.get("https://www.google.com.au/")

time.sleep(5)

driver.maximize_window()

driver.minimize_window()

driver.quit()

driver.back()

driver.forward()

driver.refresh()

driver.save_screenshot('page.png')

title = driver.title
print(title)

html = driver.page_source
print(html)

win = driver.current_window_handle
print(win)

wins = driver.window_handles
print(wins)

url = driver.current_url
print(url)
```
