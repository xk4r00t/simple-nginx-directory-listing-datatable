# nginx directory listing datatable
Simple nginx directory listing datatable allow you to use datatable on each directory listing page served by Nginx.
![Image nginx directory listing datatable](https://raw.githubusercontent.com/tgiordmaina/simple-nginx-directory-listing-datatable/master/screenshot_demo.png)

# Install
1. Edit your NGINX configuration and add these lines
```
add_before_body /ng-before.txt;
add_after_body /ng-after.txt;
autoindex on;
```

2. Put **ng-before.txt** and **ng-after.txt** on your root folder (e.g : '*/var/www/html*' (see your '*root*' param in your nginx configuration file)
