# Automation-for-User-Management-Tool-by-adding-a-user
using selenium/Phython automation new user added to user in orangeHRM user management tool

Overview
---

In this Project with the help of my python code you can navigate to orangeHRM(management tool) and add new user and login credentials automatically by using Selenium  webdriver. 

Steps to add user using Selenium for user managment tool :

Step 1:Navigating  “https://opensource-demo.orangehrmlive.com/”

Step 2: Logining with below credits
a. "Username" - "Admin"
b. "Password" - "admin123"

Step 3: Navigating to "PIM" and create a new employee

Step 4: Navigating to "Admin" section using left side panel

Step 5: Adding a new user by using step 3 details by keeping the "status" as
enabled

Step 6: Once the user is created search for the user in admin section

Step 7: Verify the user is created

Step 8: Loging out from application

Step 9: Re Login to application using step 5

Once you transfer the above steps into code using selenium module then all the steps will accomplish automatically to achieve this first you need to u nderstand what is selenium and webdriver to automate the web page.

## A deeper look at Selenium
* Selenium is an umbrella project for a range of tools and libraries that enable and support the automation of web browsers.
* Selenium controls web browsers
* Selenium is many things but at its core, it is a toolset for web browser automation that uses the best techniques available to remotely control browser instances and emulate a user’s interaction with the browser.
* Selenium allows users to simulate common activities performed by end-users; entering text into fields, selecting drop-down values and checking boxes, and clicking links in documents. It also provides many other controls such as mouse movement, arbitrary JavaScript execution, and much more.
* Although used primarily for front-end testing of websites, Selenium is, at its core, a browser user agent library. The interfaces are ubiquitous to their application, encouraging composition with other libraries to suit your purpose.

## Installation Guide
To achieve this first you need to install webdriver,Through WebDriver, Selenium supports all major browsers on the market such as Chrome, Firefox, Internet Explorer, Edge, and Safari. Where possible, WebDriver drives the browser using the browser’s built-in support for automatio since all the driver implementations except for Internet Explorer are provided by the browser vendors themselves, they are not included in the standard Selenium distribution. This section explains the basic requirements for getting started with the different browsers.

* Chrome Browser driver link - https://chromedriver.chromium.org/downloads
* Mozilla Firefox driver link - https://github.com/mozilla/geckodriver/releases
* Microsoft Edge driver link - https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/ (Downlaod Stable link)

after Downloading create the folder in your drive and move the drivers into the folder and add the path of drivers into system environmental variable path.
![image](https://user-images.githubusercontent.com/118096217/205330990-2fa22500-eb67-48da-b388-80456d98e34d.png)
![image](https://user-images.githubusercontent.com/118096217/205331561-60a333d2-e711-456e-98c2-89e32b447f0d.png)

next after successfully adding the driver into the path next install selenium module into your system library by using command
```sh
pip install selenium 
```
After successfull installation you can use selenium to automate the webpage.

Output
---

The video below show how it really works....

https://user-images.githubusercontent.com/118096217/205359042-10bf1080-59d9-4ce1-a6cc-310f424ac996.mp4

