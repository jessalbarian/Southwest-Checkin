# Southwest-Checkin
An easy python script to continuously retry checking into your Southwest flight using ChromeDriver and Selenium.  Effectively checking you in at the moment it becomes available!

### Example
	python southwest_checkin.py -c TESTER -f Testy -l McTest

### Requirements
install the selenium python library with pip via pip install -r requirements.txt
Also requires chromedriver to be in the PATH environment variable, the MAC OSX chrome driver is in this repo, other versions are available [here](https://sites.google.com/a/chromium.org/chromedriver/downloads)

### Options
	* -c the confirmation number string
	* -f the first name for the confirmation
	* -l the last name for the confirmation

### Notice
Try not to activate this script for very long if you can help it, constantly requesting webpages can cause issues for the webserver.
