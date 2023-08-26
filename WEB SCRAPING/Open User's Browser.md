
```python
def start(url):
 # Get the path to the Chrome profile directory.
  chrome_profile_dir = os.path.join(os.path.expanduser("~"), "AppData", "Local", "Google", "Chrome", "User Data")

  # Create a ChromeOptions object and set the user data directory to the logged-in profile directory.

  options = selenium.webdriver.ChromeOptions()
  options.add_argument(f"user-data-dir={chrome_profile_dir}")

  # Create a ChromeWebDriver object and pass in the ChromeOptions object.
  driver = selenium.webdriver.Chrome(options=options)
  driver.get(url)
```