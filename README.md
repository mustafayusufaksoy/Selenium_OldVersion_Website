# Selenium_OldVersion_Website
I actually wrote this code to collect benign applications. I'm doing a study on Malware Detection and I wrote this code because benign windows PE files are also needed for analysis.

This Python code uses the Selenium library to automate a web browser session and navigate to the "oldversion.com" website. It prompts the user to enter the number of apps to be downloaded and the name of the page to be scraped. Then, it automatically downloads different versions of the specified application.

The logic of the code is as follows:

It imports the necessary modules and exceptions from the Selenium library.
It prompts the user to input the number of apps to be downloaded and the name of the page to be scraped.
It configures Chrome browser options and launches the Chrome browser.
It navigates to the "oldversion.com" website and directs to the specified application page.
It clicks on the element to open the version category using the required CSS selectors.
Starting from the specified page, it automatically downloads different versions of the applications.
It clicks on the download link of each application, and the file is downloaded.
It proceeds to the next application, and this process is repeated until the specified number of apps is downloaded.
Once the process is completed, the browser session is closed, and the code terminates.
This code provides a basic example of automating file downloads by navigating through a website like "oldversion.com." It's essential to ensure that such automations comply with the usage terms and permissions of the website. Additionally, website structures may change over time, so updating the code accordingly is necessary. Caution should be exercised when modifying the code to avoid any unintended consequences. 

NOTE: I could not find a system that prevents google ads when entering the site, we have to do it manually, but if you develop a method for this and share it with me, I would be very happy.
