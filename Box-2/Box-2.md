# scan

target `10.65.159.76`
ports open:
`
21
80
2222

`
* tool used: nmap
# enumeration

directories found:
`/robots.txt, /simple`

* tool used: gobuster
# exploit
CVE: `CVE-2019-9053`

vulnerability: SQLI

credentials founded:
`
salt for pass: 1dac0d92e9fa6bb2
username: mitch
email: admin@admin.com
password: 0c01f4468bd75d7a84c7eb73846e8d96
`
* EDB-ID: 46635
# Craking the hash

hash type: MD5
hash mode: 20 ($salt,$pass)

password: secret

* tool used: hashcat
# Pwned machine

user flag: G00d j0b, keep up!
root flag: W3ll d0n3. You made it!

just needed to use a privileged shell using: `sudo vim -c ':!/bin/sh'`
