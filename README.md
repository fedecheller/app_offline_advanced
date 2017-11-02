# app_offline.html file for IIS with advanced features

adds automatic control to web site reactivation


## how to use

- on the iis web site root add the "app_offline.html" file, the site will be set in maintenance mode
- update your application data
- rename the file to "_app_offline.html" and the open offline pages reload the application


## how it work
the offline page poll the website and when with it go on-line the application will be reloaded 


## info
- the files (images, js...) that you use in the offline page need to be hosted on a different website because your will be offline!
- you can change the "window.location.href" for define the start page that will be reloaded
- you can change the "url" param to control the online page
