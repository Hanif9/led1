# led1
## Yang dibutuhkan:
```
-Apache2
-PHP
```
cara menginstallnya dapat dengan mengikuti link ini

https://pchelp.ricmedia.com/setup-lamp-server-raspberry-pi-3-complete-diy-guide/3/

instalasi cukup sampai PHP saja

## EDIT SUDOERS
buka file sudoers di
```
/etc/sudoers
```
tambahkan ini dibaris paling akhir
```
www-data ALL=(ALL) NOPASSWD:ALL
```


## file-file diletakkan dalam direktori
```
/var/www/html
```
