# Auto Login
Attempt to login to a known firewall if there is no internet connection

Use provided (inside jar) phantomJS binary or take its path as first argument.

## Configuration

`config.properties` (in working directory) format :
```
address=(firewall url)
page_title=(title of the page, leave blank to not check)
username_field_id=(DOM id if the username field)
pass_field_id=(DOM id if the password field)
button_id=(DOM id if the button)
login=(login to use, leave blank to ask)
pass=(password to use, leave blank to ask)

test_ports=80,8080 (ports to check, leave blank to skip)
test_address=http://portquiz.net (url to reach, leave blank to skip)
test_head=<html>\n<head>\n<title>Outgoing Port Tester</title> (starting of the response content)
```

## Downloads
* [Any platform (94 MB)](https://raw.githubusercontent.com/Klemek/AutoLogin/master/download/autologin-1.0.jar)
* [Linux 32bit (34 MB)](https://raw.githubusercontent.com/Klemek/AutoLogin/master/download/autologin-1.0-linux32.jar)
* [Linux 64bit (33 MB)](https://raw.githubusercontent.com/Klemek/AutoLogin/master/download/autologin-1.0-linux64.jar)
* [Windows (25 MB)](https://raw.githubusercontent.com/Klemek/AutoLogin/master/download/autologin-1.0-windows.jar)
* [MacOSX (24 MB)](https://raw.githubusercontent.com/Klemek/AutoLogin/master/download/autologin-1.0-macosx.jar)
