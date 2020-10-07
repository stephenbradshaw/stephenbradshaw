### Stephen's Github 

This is where I store my public code, most of which is related to my pentesting/security work.

Some of the more interesting items are:

- My [pentesting_stuff repository](https://github.com/stephenbradshaw/pentesting_stuff), which has a [website](https://stephenbradshaw.github.io/pentesting_stuff/) with some simple writeups on niche subjects I sometimes need reminders on, and bits of code too small for  for various pentesting tsa
- [vulnserver](https://github.com/stephenbradshaw/vulnserver). I wrote this ages ago, its a simple server app that helps you learn software exploitation. Its inexplicably still relatively popular. I have a [blog](http://www.thegreycorner.com/) that has some articles describing how to exploit some of the vulnerabilities.
- [breakableflask](https://github.com/stephenbradshaw/breakableflask), a simple single file vulnerable web app that was designed to be used as a target for me to test exploitation tools against. Also works as a learning tool.
- Ive written new Burp extensions, and modified existing ones in Java and Python. Many have very niche uses, but even though I dont use them very often they do serve as good examples of how to write/modify extensions yourself. Examples [here](https://github.com/stephenbradshaw/CSIG), [here](https://github.com/stephenbradshaw/burpextensiontemplates), [here](https://github.com/stephenbradshaw/espresso), [here](https://github.com/stephenbradshaw/Burp-Response-Handler), [here](https://github.com/stephenbradshaw/absentis) and [here](https://github.com/stephenbradshaw/pentesting_stuff/blob/master/burp_extensions/saver.py).
- [This](https://github.com/stephenbradshaw/letsencrypt_dns01_server) is a DNS server I wrote to facilitate the process of obtaining wildcard certificates from LetsEncrypt using the DNS01 protocol. I wanted something small and dedicated to purpose as I was running it on a system that was making several non traditional uses of DNS, including a dedicated Burp Collaborator server and a DNS tunneling service. To help route the DNS requests I also modified [this](https://github.com/stephenbradshaw/dns-reverse-proxy) to route DNS requests based on type. 
