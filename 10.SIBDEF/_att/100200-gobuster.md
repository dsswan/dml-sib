```sh
┌──(dml㉿kali)-[~]
└─$ gobuster dir -u http://92.51.39.106:8050 -w /usr/share/wordlists/dirb/common.txt -x php,txt,html,bak,old

===============================================================
Gobuster v3.8.2
by OJ Reeves (@TheColonial) & Christian Mehlmauer (@firefart)
===============================================================
[+] Url:                     http://92.51.39.106:8050
[+] Method:                  GET
[+] Threads:                 10
[+] Wordlist:                /usr/share/wordlists/dirb/common.txt
[+] Negative Status codes:   404
[+] User Agent:              gobuster/3.8.2
[+] Extensions:              old,php,txt,html,bak
[+] Timeout:                 10s
===============================================================
Starting gobuster in directory enumeration mode
===============================================================
.hta.bak             (Status: 403) [Size: 289]
.hta                 (Status: 403) [Size: 285]
.hta.old             (Status: 403) [Size: 289]
.hta.php             (Status: 403) [Size: 289]
.hta.txt             (Status: 403) [Size: 289]
.htaccess.php        (Status: 403) [Size: 294]
.htaccess            (Status: 403) [Size: 290]
.hta.html            (Status: 403) [Size: 290]
.htaccess.txt        (Status: 403) [Size: 294]
.htaccess.html       (Status: 403) [Size: 295]
.htaccess.bak        (Status: 403) [Size: 294]
.htpasswd            (Status: 403) [Size: 290]
.htaccess.old        (Status: 403) [Size: 294]
.htpasswd.txt        (Status: 403) [Size: 294]
.htpasswd.html       (Status: 403) [Size: 295]
.htpasswd.bak        (Status: 403) [Size: 294]
.htpasswd.old        (Status: 403) [Size: 294]
.htpasswd.php        (Status: 403) [Size: 294]
about.php            (Status: 200) [Size: 2251]
action               (Status: 200) [Size: 80668]
admin                (Status: 301) [Size: 318] [--> http://92.51.39.106:8050/admin/]
calendar.php         (Status: 200) [Size: 2609]
cart                 (Status: 301) [Size: 317] [--> http://92.51.39.106:8050/cart/]
cgi-bin/             (Status: 403) [Size: 289]
cgi-bin/.txt         (Status: 403) [Size: 293]
cgi-bin/.php         (Status: 403) [Size: 293]
cgi-bin/.html        (Status: 403) [Size: 294]
cgi-bin/.bak         (Status: 403) [Size: 293]
cgi-bin/.old         (Status: 403) [Size: 293]
comments             (Status: 301) [Size: 321] [--> http://92.51.39.106:8050/comments/]
css                  (Status: 301) [Size: 316] [--> http://92.51.39.106:8050/css/]
error.php            (Status: 200) [Size: 2386]
guestbook.php        (Status: 200) [Size: 3313]
images               (Status: 301) [Size: 319] [--> http://92.51.39.106:8050/images/]
include              (Status: 500) [Size: 611]
index.php            (Status: 200) [Size: 3362]
index.php            (Status: 200) [Size: 3362]
pictures             (Status: 301) [Size: 321] [--> http://92.51.39.106:8050/pictures/]
server-status        (Status: 403) [Size: 294]
test.php             (Status: 200) [Size: 142]
tos.php              (Status: 200) [Size: 37619]
upload               (Status: 301) [Size: 319] [--> http://92.51.39.106:8050/upload/]
users                (Status: 301) [Size: 318] [--> http://92.51.39.106:8050/users/]
Progress: 27678 / 27678 (100.00%)
===============================================================
Finished
===============================================================
                                                                                               
┌──(dml㉿kali)-[~]
└─$ gobuster dir -u http://92.51.39.106:7788 -w /usr/share/wordlists/dirb/common.txt -x py,json,html

===============================================================
Gobuster v3.8.2
by OJ Reeves (@TheColonial) & Christian Mehlmauer (@firefart)
===============================================================
[+] Url:                     http://92.51.39.106:7788
[+] Method:                  GET
[+] Threads:                 10
[+] Wordlist:                /usr/share/wordlists/dirb/common.txt
[+] Negative Status codes:   404
[+] User Agent:              gobuster/3.8.2
[+] Extensions:              py,json,html
[+] Timeout:                 10s
===============================================================
Starting gobuster in directory enumeration mode
===============================================================
index.html           (Status: 200) [Size: 15053]
index.html           (Status: 200) [Size: 15053]
login.html           (Status: 200) [Size: 4749]
read                 (Status: 200) [Size: 6596]
search               (Status: 200) [Size: 3504]
server.html          (Status: 200) [Size: 4520]
upload               (Status: 405) [Size: 325]
Progress: 18452 / 18452 (100.00%)
===============================================================
Finished
===============================================================
                                                                                               
┌──(dml㉿kali)-[~]
└─$ 
```
