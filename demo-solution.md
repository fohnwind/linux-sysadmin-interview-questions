
####[[>_<]](#toc) <a name='demo'>Demo Answer</a>

* Unpack test.tar.gz without man pages or google.
	- `# tar -jxvf test.tar.gz`
* Remove all "*.pyc" files from testdir recursively?
	- `# rm -f testdir/*.pyc`
* Search for "my konfu is the best" in all *.py files.
	- `# grep -n "my konfu is the best" *.py`
* Replace the occurrence of "my konfu is the best" with "I'm a linux jedi master" in all *.txt files.
	- `# sed -i "s/my konfu is the best/I\'m a linux jedi master" *.txt`
* Test if port 443 on a machine with IP address X.X.X.X is reachable.
	- `# nmap -p 443 X.X.X.X`
* Get http://myinternal.webserver.local/test.html via telnet.
	- `# telnel http://myinternal.webserver.local/ 80`
	- `> GET /test.html HTTP/1.0`
* How to send an email without a mail client, just on the command line?
* Write a ```get_prim``` method in python/perl/bash/pseudo.
* Find all files which have been accessed within the last 30 days.
* Explain the following command ```(date ; ps -ef | awk ‘{print $1}’ | sort | uniq | wc -l ) >> Activity.log```
* Write a script to list all the differences between two directories.
* In a log file with contents as ```<TIME> : [MESSAGE] : [ERROR_NO] - Human readable text``` display summary/count of specific error numbers that occured every hour or a specific hour.

