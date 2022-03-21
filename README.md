# Virtual Private Server
*Do you ever just get tired of your school blocking your favorite websites well this code is the solution for you, today I will like to show you how to setup and browse your favorite websites with ease*
*This tutorial is very simple to follow ;)*

## 📝 Requirements
* Internet Access
* [Replit Account](https://replit.com/signup)
* Phone / Computer (Computer Recommended)

## 💪 Setup
* Go to [Replit](https://replit.com)
* Create a new repl and choose **Python** as the programming language
* Once the new repl is created you should see a `main.py` file
* Open the `main.py` file don't worry about the `poetry.lock` and `pyproject.toml` files
* Once you are in the `main.py` file paste the following code in
```python
from selenium import webdriver
from selenium.webdriver.chrome.options import Options

chrome_options = Options()
chrome_options.add_argument('--no-sandbox')
chrome_options.add_argument('--disable-dev-shm-usage')

driver = webdriver.Chrome(options=chrome_options)
driver.get("https://google.com") # Default website when the code is running
```
* Once pasted click the green `▶️ Run` button on the top middle and you should see a browser window in the output on the top right corner of the screen
* 🎉 Congratulations you have successfully bypassed your school website blocker
