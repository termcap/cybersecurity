# cybersecurity

nmap -A -p- <- all ports even beyond 1000, whats running on those ports 
name -A -p21 <- Whats going on on port 21
msfvenom <- generate payload for reverse shells
hydra -t 4 -l dale -P /usr/share/wordlists/rockyou.txt -vV 10.10.10.6 ftp <- tool for bruteforcing passwords for supported services, here ftp is being bruteforced for user dale from password list rockyou.txt
