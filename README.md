# Firefox-Win11-Dark-Integration
A firefox theme integrating windows 11 dark colors + a custom userchrome used to fix context menus not being themed by firefox color themes by default.

![image](https://github.com/0ddfactory/Firefox-Win11-Dark-Integration/assets/25939455/9cc772f2-7c9b-44a9-93ea-3ee5e5dc5232)

## Installation

Install firefox theme from:   
https://addons.mozilla.org/en-US/firefox/addon/windows-11-dark-integration/

### Fix Context Menus (right click menu)

Download userChrome.css & userContent.css from this github page.  
* In Firefox type about:config in url bar and hit enter:  
![image](https://github.com/0ddfactory/Firefox-Win11-Dark-Integration/assets/25939455/2c742708-6d79-44b6-8565-be3b69135705)  
* Search for "toolkit.legacyUserProfileCustomizations.stylesheets" and set to true
* Open File Explorer  
* Enter "%appdata%\Mozilla\Firefox\Profiles" in the directory bar like so:  
![image](https://github.com/0ddfactory/Firefox-Win11-Dark-Integration/assets/25939455/fd5a2438-3986-4981-a909-26be3420730f)
* Click into ********.default-release folder  
* Create a new folder called chrome in this directory  
* Navigate into the chrome folder you just created and paste the downloaded userChrome.css & userContent.css into the directory
* Restart Firefox :) 

