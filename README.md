

Django implementation of anyorigin.com (Not Working CUrrently)    
Uses Django, [requests lib](http://docs.python-requests.org/en/latest/) and [tor](https://www.torproject.org/)

**what is the difference between anyorigin.com and alloworigin.com?**  
Well, while alloworigin.com is open source and free to use,  
anyorigin.com is closed source and not free.

**whateverorigin.org is open source and free, why use alloworigin.com?**  
whateverorigin.org is a good alternative to anyorigin.com, but  
it has not been maintained well, thus some basic functions remain [broken](https://github.com/ripper234/Whatever-Origin/issues/10)  
this is an attempt to resurrect anyorigin and adding additional features


**Post Upgrade features**  
1. anonymous get request using tor   
2. reduce change of getting banned from a site using tor  
3. compress content using zlib [Broken]  

***Upgrades***
1.Django 3.1
2. TODO


**usage**  
basic usage  
http://alloworigin.com/get?url=http://example.com
  
with callback  
http://alloworigin.com/get?url=http://example.com&callback=foo

anonymous request using tor, with callback   
http://alloworigin.com/get?url=http://example.com&callback=foo&tor=1

enable base64 zlib, utf8 compatible compression
http://alloworigin.com/get?url=http://example.com&compress=1

***this is not hosted anywhere currently, but i will be hosting it on herokuu when i can***

***thanks to [Bill](https://github.com/Eiledon) and [Ron](https://github.com/ripper234/) for developing it in the first place ***