Linux System Administrator/DevOps Interview Questions
====================================================

A collection of linux sysadmin/devops interview questions. Feel free to contribute via pull requests, issues or email messages.


## <a name='toc'>Table of Contents</a>

  1. [Contributors](#contributors)
  1. [General Questions](#general)
  1. [Simple Linux Questions](#simple)
  1. [Medium Linux Questions](#medium)
  1. [Hard Linux Questions](#hard)
  1. [Expert Linux Questions](#expert)
  1. [Networking Questions](#network)
  1. [MySQL Questions](#mysql)
  1. [DevOps Questions](#devop)
  1. [Fun Questions](#fun)
  1. [Demo Time](#demo)
  1. [Other Great References](#references)


#### [[⬆]](#toc) <a name='contributors'>Contributors:</a>

* [moregeek](https://github.com/moregeek)
* [typhonius](https://github.com/typhonius)
* [schumar](https://github.com/schumar)
* [negesti](https://github.com/negesti)
* peter
* [andreashappe](https://github.com/andreashappe)
* [quatrix](https://github.com/quatrix)
* [biyanisuraj](https://github.com/biyanisuraj)
* [pedroguima](https://github.com/pedroguima)
* Ben
* [bharatnc](https://github.com/bharatnc)


#### [[⬆]](#toc) <a name='general'>General Questions:</a>

* What did you learn yesterday/this week?
* Talk about your preferred development/administration environment. (OS, Editor, Browsers, Tools etc.)
* Tell me about the last major Linux project you finished.
* Tell me about the biggest mistake you've made in [some recent time period] and how you would do it differently today. What did you learn from this experience?
* Why we must choose you?
* What function does DNS play on a network?
* What is HTTP?
* What is an HTTP proxy and how does it work?
* Describe briefly how HTTPS works.
* What is SMTP? Give the basic scenario of how a mail message is delivered via SMTP.
* What is RAID? What is RAID0, RAID1, RAID5, RAID10?
* What is a level 0 backup? What is an incremental backup?
* Describe the general file system hierarchy of a Linux system.
* What does the term "DevOps" mean to you?
* "Hard"/hands-on/SRE vs
* "Soft"/Three Ways/Theory of Constraints/philosophy of DevOps
* Describe your experience with task management
  - Agile
  - Kanban
  - Waterfall
* What drew you to DevOps
* Describe the most challenging situation that you were faced with and how did you fix it?
* How do you stay current?


#### [[⬆]](#toc) <a name='simple'>Simple Linux Questions:</a>

* What is the name and the UID of the administrator user?
* How to list all files, including hidden ones, in a directory?
* What is the Unix/Linux command to remove a directory and its contents?
* Which command will show you free/used memory? Does free memory exist on Linux?
* How to search for the string "my konfi is the best" in files of a directory recursively?
* How to connect to a remote server or what is SSH?
* How to get all environment variables and how can you use them?
* I get "command not found" when I run ```ifconfig -a```. What can be wrong?
* What happens if I type TAB-TAB?
* What command will show the available disk space on the Unix/Linux system?
* What commands do you know that can be used to check DNS records?
* What Unix/Linux commands will alter a files ownership, files permissions?
* What does ```chmod +x FILENAME``` do?
* What does the permission 0750 on a file mean?
* What does the permission 0750 on a directory mean?
* How to add a new system user without login permissions?
* How to add/remove a group from a user?
* What is a bash alias?
* How do you set the mail address of the root/a user?
* What does CTRL-c do?
* What is in /etc/services?
* How to redirect STDOUT and STDERR in bash? (> /dev/null 2>&1)
* What is the difference between UNIX and Linux.
* What is the difference between Telnet and SSH?
* Explain the three load averages and what do they indicate. What command can be used to view the load averages?
* Can you name a lower-case letter that is not a valid option for GNU ```ls```?
* What is a Linux kernel module?
* Walk me through the steps in booting into single user mode to troubleshoot a problem.
* Walk me through the steps you'd take to troubleshoot a 404 error on a web application you administer.

#### [[⬆]](#toc) <a name='medium'>Medium Linux Questions:</a>

* What do the following commands do and how would you use them?
 * ```tee```
 * ```awk```
 * ```tr```
 * ```cut```
 * ```tac```
 * ```curl```
 * ```wget```
 * ```watch```
 * ```head```
 * ```tail```
* What does an ```&``` after a command do?
* What does ```& disown``` after a command do?
* What is a packet filter and how does it work?
* What is Virtual Memory?
* What is swap and what is it used for?
* What is an A record, an NS record, a PTR record, a CNAME record, an MX record?
* Are there any other RRs and what are they used for?
* What is a Split-Horizon DNS?
* What is the sticky bit?
* What does the immutable bit do to a file?
* What is the difference between hardlinks and symlinks? What happens when you remove the source to a symlink/hardlink?
* What is an inode and what fields are stored in an inode?
* How to force/trigger a file system check on next reboot?
* What is SNMP and what is it used for?
* What is a runlevel and how to get the current runlevel?
* What is SSH port forwarding?
* What is the difference between local and remote port forwarding?
* What are the steps to add a user to a system without using useradd/adduser?
* What is MAJOR and MINOR numbers of special files?
* Describe the mknod command and when you'd use it.
* Describe a scenario when you get a "filesystem is full" error, but 'df' shows there is free space.
* Describe a scenario when deleting a file, but 'df' not showing the space being freed.
* Describe how 'ps' works.
* What happens to a child process that dies and has no parent process to wait for it and what’s bad about this?
* Explain briefly each one of the process states.
* How to know which process listens on a specific port?
* What is a zombie process and what could be the cause of it?
* You run a bash script and you want to see its output on your terminal and save it to a file at the same time. How could you do it?
* Explain what echo "1" > /proc/sys/net/ipv4/ip_forward does.
* Describe briefly the steps you need to take in order to create and install a valid certificate for the site https://foo.example.com.
* Can you have several HTTPS virtual hosts sharing the same IP?
* What is a wildcard certificate?
* Which Linux file types do you know?
* What is the difference between a process and a thread? And parent and child processes after a fork system call?
* What is the difference between exec and fork?
* What is "nohup" used for?
* What is the difference between these two commands?
 * ```myvar=hello```
 * ```export myvar=hello```
* How many NTP servers would you configure in your local ntp.conf?
* What does the column 'reach' mean in ```ntpq -p``` output?
* You need to upgrade kernel at 100-1000 servers, how you would do this?
* How can you get Host, Channel, ID, LUN of SCSI disk?
* How can you limit process memory usage?
* What is bash quick substitution/caret replace(^x^y)?
* Do you know of any alternative shells? If so, have you used any?
* What is a tarpipe (or, how would you go about copying everything, including hardlinks and special files, from one server to another)?
* How can you tell if the httpd package was already installed?
* How can you list the contents of a package?
* How can you determine which package is better: openssh-server-5.3p1-118.1.el6_8.x86_64 or openssh-server-6.6p1-1.el6.x86_64 ?
* Can you explain to me the difference between block based, and object based storage?

#### [[⬆]](#toc) <a name='hard'>Hard Linux Questions:</a>

* What is a tunnel and how you can bypass a http proxy?
* What is the difference between IDS and IPS?
* What shortcuts do you use on a regular basis?
* What is the Linux Standard Base?
* What is an atomic operation?
* Your freshly configured http server is not running after a restart, what can you do?
* What kind of keys are in ~/.ssh/authorized_keys and what it is this file used for?
* I've added my public ssh key into authorized_keys but I'm still getting a password prompt, what can be wrong?
* Did you ever create RPM's, DEB's or solaris pkg's?
* What does ```:(){ :|:& };:``` do on your system?
* How do you catch a Linux signal on a script?
* Can you catch a SIGKILL?
* What's happening when the Linux kernel is starting the OOM killer and how does it choose which process to kill first?
* Describe the linux boot process with as much detail as possible, starting from when the system is powered on and ending when you get a prompt.
* What's a chroot jail?
* When trying to umount a directory it says it's busy, how to find out which PID holds the directory?
* What's LD_PRELOAD and when it's used?
* You ran a binary and nothing happened. How would you debug this?
* What are cgroups? Can you specify a scenario where you could use them?
* How can you remove/delete a file with file-name consisting of only non-printable/non-type-able characters?
* How can you increase or decrease the priority of a process in Linux?
* What are run-levels in Linux?


#### [[⬆]](#toc) <a name='expert'>Expert Linux Questions:</a>

* A running process gets ```EAGAIN: Resource temporarily unavailable``` on reading a socket. How can you close this bad socket/file descriptor without killing the process?


#### [[⬆]](#toc) <a name='network'>Networking Questions:</a>

* What is localhost and why would ```ping localhost``` fail?
* What is the similarity between "ping" & "traceroute" ? How is traceroute able to find the hops.
* What is the command used to show all open ports and/or socket connections on a machine?
* Is 300.168.0.123 a valid IPv4 address?
* Which IP ranges/subnets are "private" or "non-routable" (RFC 1918)?
* What is a VLAN?
* What is ARP and what is it used for?
* What is the difference between TCP and UDP?
* What is the purpose of a default gateway?
* What is command used to show the routing table on a Linux box?
* A TCP connection on a network can be uniquely defined by 4 things. What are those things?
* When a client running a web browser connects to a web server, what is the source port and what is the destination port of the connection?
* How do you add an IPv6 address to a specific interface?
* You have added an IPv4 and IPv6 address to interface eth0. A ping to the v4 address is working but a ping to the v6 address gives you the response ```sendmsg: operation not permitted```. What could be wrong?
* What is SNAT and when should it be used?
* Explain how could you ssh login into a Linux system that DROPs all new incoming packets using a SSH tunnel.
* How do you stop a DDoS attack?
* How can you see content of an ip packet?
* What is IPoAC (RFC 1149)?
* Say I open a web browser and enter an address. I hit enter. Describe how the connection the works in as much detail as possible. Trying to hear that they understand:
  * DNS
  * Network routing
  * Load Balancing
  * Ports on server
  * Service that is serving port
* What’s a PTR in DNS?
* What’s a MX record in DNS?
* How a CDN chooses the closest host to serve a client?
* In which cases would you choose to not implement a CDN?
* How do you measure the performance of a server/web application? (tools, methods)
* What are secure ways to SSH to a server inside a private network from a public location?
* Using the OSI model, which layer has the responsibility of making sure that the packet gets where it is supposed to go?

	What is the subnet mask, network address and broadcast address for the following address: 123.65.47.62/22?

	What command is used to show all open ports and/or socket connections on a machine?

	What is NAT? What is it used for?

	Which IP ranges/subnets are "private" or "non-routable" (RFC 1918)?

	What is a packet filter and how does it work?

	What is a proxy and how does it work?

	What is ARP and what is it used for?

	What is the difference between TCP and UDP?

	What command is used to show the route table for a machine?

	Explain asynchronous routing?

	What is the purpose of a default gateway?

	A TCP connection on a network can be uniquely defined by 4 things. What are those things?

	When a client running a web browser connects to a web server, what is the source port of the connection?

	What is the destination port of the connection?

	What is SMTP?

	What is an SMTP relay?

	Give the basic scenario of how a mail message is delivered via SMTP

	What function does DNS play on a network?

	What is an A record?

	What is an NS record?

	What is an MX record?

	What is a PTR record?

	What is a DNS forwarder?

	What command is used to lookup DNS records?

	What is meant by "Reverse Lookup"?

	What is LDAP and what is it used for?

	What is a DN in LDAP?

	What is SSH?

	What is SSL?

	What is IDS?

	What is IPS?

	What is the difference between IDS and IPS?

	What is meant by the term "DOS Attack"?

	What is RAID?

	What is swap and what is it used for?

	What command will show the available disk space on the Unix/Linux system?

	How do you determine the public and prive IP addresses, if applicable, of a Unix/Linux system from the command line?

	What Unix/Linux command will alter a file's ownership?

	What Unix/Linux command will alter a file's permissions?

	What Unix/Linux command will show all processes running on a system?

	What Unix/Linux command will show the details of a file(permissions, size, timestamp)?

	What Unix/Linux command would you use to list all currently loaded kernel modules?

	What command would you use to telnet to port 7777 on a machine with IP address 10.10.10.128?

	What Unix/Linux command(s) will show a system's current resource allocations?

	What is the Unix/Linux command to remove a directory and its contents?

	What is the name and location of the system log on a Unix or Linux system?

	What would you do to recover a lost the root password to a Unix/Linux system?

	What is the difference between hardlink and symlink?

	What happens when you remove the source to a symlink?

	What are some of the security risks of symlinks?

	Explain a hardlink

	Where is a filename stored?

	What happens when a hardlink is removed

	how do you know when a file is removed

	Write a locking function in bash

	What is a pre-emptive kernel, what does that mean to you?

	What is an atomic operation?

	How does a switch get a mac address?

	What type of packet to discover a router?

	How does traceroute work?

	A careless sysadmin executes the following command: chmod 444 chmod - what do you do to fix this?



#### [[⬆]](#toc) <a name='mysql'>MySQL questions:</a>

* How do you create a user?
* How do you provide privileges to a user?
* What is the difference between a "left" and a "right" join?
* Explain briefly the differences between InnoDB and MyISAM.
* Describe briefly the steps you need to follow in order to create a simple master/slave cluster.
* Why should you run "mysql_secure_installation" after installing MySQL?
* How do you check which jobs are running?
* How would you take a backup of a MySQL database?

#### [[⬆]](#toc) <a name='devop'>DevOps Questions:</a>

* Can you describe your workflow when you create a script?
* What is GIT?
* What is a dynamically/statically linked file?
* What does "./configure && make && make install" do?
* What is puppet/chef/ansible used for?
* What is Nagios/Zenoss/NewRelic used for?
* What is Jenkins/TeamCity/GoCI used for?
* What is the difference between Containers and VMs?
* How do you create a new postgres user?
* What is a virtual IP address? What is a cluster?
* How do you print all strings of printable characters present in a file?
* How do you find shared library dependencies?
* What is Automake and Autoconf?
* ./configure shows an error that libfoobar is missing on your system, how could you fix this, what could be wrong?
* What are the advantages/disadvantages of script vs compiled program?
* What's the relationship between continuous delivery and DevOps?
* What are the important aspects of a system of continuous integration and deployment?
* How would you enable network file sharing within AWS that would allow EC2 instances in multiple availability zones to share data?
* Are you familiar with CI tools? Which ones?
* Describe your experience implementing continuous deployment
* How do you setup an end-to-end pipeline from dev to deployment? (long answer)
  * How can Docker help in this case?
* How frequently have you been deploying?
  * Have you been able to improve the frequency of deployments? If so, how?


#### [[⬆]](#toc) <a name='fun'>Fun Questions:</a>

* A careless sysadmin executes the following command: ```chmod 444 /bin/chmod ``` - what do you do to fix this?
* I've lost my root password, what can I do?
* I've rebooted a remote server but after 10 minutes I'm still not able to ssh into it, what can be wrong?
* If you were stuck on a desert island with only 5 command-line utilities, which would you choose?
* You come across a random computer and it appears to be a command console for the universe. What is the first thing you type?
* Tell me about a creative way that you've used SSH?
* You have deleted by error a running script, what could you do to restore it?
* What will happen on 19 January 2038?
* How to reboot server when reboot command is not responding?
* Do you have any side projects?
* If you could learn any technology now, what would be?


#### Security Questions

* Difference between authorization and authentication?
* Describe two-factor authentication
* Describe how would you secure a web application
  * HTTP vs HTTPS
* Talk about PKI/your experience with SSL/Certificates

#### Cloud Questions

* Have you used AWS or other cloud platforms?
  * How long for?
  * In production or just at home on personal projects?
* How to keep logs on servers or containers with ephemeral storage?
* Where to look when trying to reduce cloud costs without reducing capacity?
* Name the "Big Three" cloud providers
  * AWS
  * GCE
  * Azure




##### AWS Questions

* Describe the advantages/disadvantages of using CloudFormation to manage your resources
* Would you use CloudFormation to create a RDS database?
* Describe EC2 spot instances and which use cases it can be used to reduce costs
* Talk about IAM roles
* Talk about VPC's
  * Subnets
  * Internet Gateways
  * NATing
  * NACL's
  * VPN/VPC Peering

#### Database Questions

* What's the use case for a database read replica?

#### Architecture Questions

* How to scale a database without just increasing capacity of a single machine while maintaining [ACID](http://en.wikipedia.org/wiki/ACID)?
* How to choose between relational database and noSQL?
* What advantages a NoSQL database like MongoDB has, comparing to MySQL?
* How to manage API versions?
* How to reduce load time of a dynamic website?
* How to reduce load time of a static website?

#### Automation Questions

* Have you used Puppet, Chef, Salt or Ansible?
  * How long have you used it for?
  * Have you used it in production?
* Describe the size of the environment that you automated (how many servers, small scale or large scale)

#### CI Questions


#### Coding Questions

* Describe a dev/test/production workflow using GIT
  * Feature branching vs trunk based development
  * Advantages of requiring pull requests and approvals
* More on [Front-end Developer Job Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/README.md)

#### Fun Questions



#### [[⬆]](#toc) <a name='demo'>Demo Time:</a>

* Unpack test.tar.gz without man pages or google.
* Remove all "*.pyc" files from testdir recursively?
* Search for "my konfu is the best" in all *.py files.
* Replace the occurrence of "my konfu is the best" with "I'm a linux jedi master" in all *.txt files.
* Test if port 443 on a machine with IP address X.X.X.X is reachable.
* Get http://myinternal.webserver.local/test.html via telnet.
* How to send an email without a mail client, just on the command line?
* Write a ```get_prim``` method in python/perl/bash/pseudo.
* Find all files which have been accessed within the last 30 days.
* Explain the following command ```(date ; ps -ef | awk '{print $1}' | sort | uniq | wc -l ) >> Activity.log```
* Write a script to list all the differences between two directories.
* In a log file with contents as ```<TIME> : [MESSAGE] : [ERROR_NO] - Human readable text``` display summary/count of specific error numbers that occurred every hour or a specific hour.


#### [[⬆]](#toc) <a name='references'>Other Great References:</a>

Some questions are 'borrowed' from other great references like:

* https://github.com/darcyclarke/Front-end-Developer-Interview-Questions
* https://github.com/kylejohnson/linux-sysadmin-interview-questions/blob/master/test.md
* http://slideshare.net/kavyasri790693/linux-admin-interview-questions
