# app_offline.html file for IIS with advanced features

adds automatic control to web site reactivation


## how to use

- on the iis web site root add the "app_offline.html" file, the site will be set in maintenance mode
- update your application data
- rename the file to "_app_offline.html"


## how it work
the offline page poll the website and when with it go on-line the application will be reloaded 
