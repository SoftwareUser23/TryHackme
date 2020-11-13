# Pickle Rick 

# Date - Software_User , MON 13 JUL 2020 

# IP - ` `

# Scanning - 

# NMAP -

"""
22 - ssh 
80 - http 

`Scan reveals its an Ubuntu box `

"""

# Web Page -

"""
Source code reveals an Username 

`Username: R1ckRul3s`

"""
# Dir bruteforce - 


"""
got some dirs using gobuster 

```
/login.php
/assets 
/robots.txt 
/server-status 
/index.html 

```
weird text in robots.txt 

```
weird txt - `Wubbalubbadubdub`
```
"""

# Using weird text and username as creds at login.php -

"""
Got succesfully login in webpage now  i have admin access 

we can execute commands through command panel 

"""

# Getting rev shell using command panel - 


""""
we don't have permission to execute nc i think 

also python rev shell isnt working 

tried php python bash nc everythin but perl is installed in box we can try perl rev shell 

hehe, got shell through perl 

got first flag

`mr. meeseek hair`

LOL we can execute any command with sudo without any password

`(ALL) NOPASSWD: ALL` 

""""

# Answers -

"""
1. ` What is the first ingredient Rick needs?`

mr. meeseek hair

2. `Whats the second ingredient Rick needs?`

1 jerry tear

3. `Whats the final ingredient Rick needs?`

fleeb juice


`Pretty easy and nice box `