### Add String To Line

This script helps you when you have multiple text file and dont know how to add word or any string between them in same line 

For example you have a host file like that:
```
1.1.1.1
test.com
132.53.12.98
```
and you want to add ports for each host, so you have other port numbers file:
```
8080
443
4008
```
By using this script you combine both text file to add ports to hosts or hosts to port with (:) string:
```
1.1.1.1:8080
test.com:443
132.53.12.98:4008
```
OR you have text file that have urls inside:
```
http://google.com/test
http://fb.com/astl
http://targets.org/index
```
and a text that contains a parameters value:
```
true
admin
member
```
you can edit the scripts `echo "$i":"$1"` to `echo "$i"?param="$1"` and make this url list:
```
http://google.com/test?param=true
http://fb.com/astl?param=admin
http://targets.org/index?param=member
```
And more.
