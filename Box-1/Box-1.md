# scan

target ip:(`10.201.0.121`)
open ports
`
22
80
139
445
`
* tool used: nmap 

# directory enumeration 

found a directory with a name development that give me usernames

usernames:`j` `k`

* tool used: gobuster

# enumeratiom

found the completed usernames 

usernames `kay` `jan`

* tool used: enum4linux
# brute forcing

password `armando`

* tool used: hydra

# privilege escalation

found a id-rsa file in `/home/kay/.ssh/id_rsa`

* tool used: linpeas

# hashing

password i get hashing the id_rsa file

`beeswax`

* tool used: johntheripper
