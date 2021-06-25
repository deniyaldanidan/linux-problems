## While using laravel8x i need to use sqlite but it gives me error [could not find driver]
so 
> i checked php.ini and found out that extensions related to sqlite are commented out so i uncomment them and restarted the server
but still no changes in error. so found out i need **php-sqlite pack**.
so i tried running `sudo apt-get install php7.4-sqlite`
but it gives errors so we have to install below packages
  `sudo apt-get install libegl1 libgl1 libgles2 libglx0 libglvnd0 libopengl0 libpcrecpp0v5 proj-data libproj15`
then we ran the command
`sudo apt-get install php7.4-sqlite`
after that restarted the apache2 server
**PROBLEM SOLVED**
