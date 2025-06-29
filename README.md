# Software-Testing_Project4
# Cross-Browser Testing using BrowserStack

This project performs **automated cross-browser testing** on a sample login page using **Selenium WebDriver** and **BrowserStack’s cloud infrastructure**. The goal is to ensure consistent behavior across multiple browsers and operating systems.

##  Tools & Technologies Used

 Java  
 Selenium WebDriver  
 BrowserStack Selenium Grid  
 Browsers Tested: Chrome, Firefox, Safari, Edge  
 Test Website: [Practice Test Login Page](https://www.saucedemo.com/)



##  Browsers and OS Tested

Browser   Version  OS          Result  Remarks                             

 Chrome    Latest   Windows 10  Pass  Everything worked fine              
 Firefox   Latest   Windows 10  Pass  No layout issues                    
 Safari    15       macOS       Minor  Slight delay in button response     
 Edge     Latest   Windows 10   Pass  UI shifted slightly at login screen 



##  How It Works

 Connects to BrowserStack's Selenium Grid using a secure hub URL  
 Executes the same login test across different browser and OS combinations  
 Verifies successful login and reports results  



##  BrowserStack Configuration

Replace the placeholders with your actual BrowserStack credentials in the code:
java
public static final String USERNAME = "your_browserstack_username";
public static final String AUTOMATE_KEY = "your_browserstack_accesskey";
Login test passed on Chrome
Login test passed on Firefox
Login test passed on Edge
Login test passed with minor delay on Safari
