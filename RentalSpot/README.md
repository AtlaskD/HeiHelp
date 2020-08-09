# How to configure

## php
* Download and run xmapp
* Enter xampp/htdocs, `git clone https://github.com/IvySYChen/heihei.git`
* 从control panel打开Apache的config - httpd.conf
* Find `DocumentRoot "/xampp/htdocs"`, change it to `DocumentRoot "/xampp/htdocs/heihei/RentalSpot"`
* Find `DirectoryIndex`, Add `Homepage.html`, put it in the first entry

## Sqlite3
* Open xampp/php/php
* Find `extension=sqlite3`, Remove `;`

# 访问网站

* 从control panel Start Apache
* 在浏览器访问localhost
