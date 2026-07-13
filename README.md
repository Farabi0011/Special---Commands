# Special---Commands
# Navigation  And  File  Management  
# 1. Show current directory
pwd

# 2. List directory contents
ls -la

# 3. Change directory
cd /var/www/html

# 4. Copy files or directories
cp file.txt /tmp/

# 5. Move or rename files
mv old.txt new.txt

# 6. Remove files or directories
rm -rf test/

# 7. Show file contents
cat /etc/passwd

# 8. Edit text files
nano config.txt

# 9. Create empty file
touch hello.txt

# 10. Create a directory
mkdir myfolder


User And permission  Management 
# 1. Show current user
whoami

# 2. Show user and group IDs
id

# 3. Run command as root
sudo apt update

# 4. Change file permissions
chmod 755 script.sh

# 5. Change password
passwd user

Networking Commands
# 1. Check network connectivity
ping google.com

# 2. Show IP addresses
ifconfig

# 3. Show open ports
ss -tuln

# 4. Scan network
nmap -sV 192.168.1.1

# 5. Download or fetch from web
curl http://example.com

# 6. Trace network path
traceroute google.com

# 7. DNS lookup
dig example.com

File Search And Manipulation 
# 1. Search files
find / -name "*.php"

# 2. Search inside files
grep "admin" config.php

# 3. Quickly find files
locate php.ini

# 4. Detect file type
file shell

# 5. View command history
history | grep nmap

Privilege Escalation Enumeration 
# 1. List sudo permissions
sudo -l

# 2. Running processes
ps aux | grep apache

# 3. Kernel/system info
uname -a

# 4. Show environment variables
env

Tool Use And Exploitation 
# 1. Start Metasploit Framework
msfconsole

# 2. Brute force tool
hydra -l admin -P passwords.txt 192.168.1.5 ssh

# 3. Password cracker
john --wordlist=rockyou.txt hashes.txt

# 4. Web server scanner
nikto -h http://target

# 5. SQL injection automation
sqlmap -u "http://site.com?id=1" --dbs

# 6. Web proxy (GUI tool)
burpsuite

# 7. Directory bruteforcing
gobuster dir -u http://site -w wordlist.txt

# 8. Packet sniffer (GUI)
wireshark
