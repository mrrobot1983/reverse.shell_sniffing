*New Findings/ Tips

Working this project on OracleVMware Kali Linux requires your attacker machine to connect to the bridged adapter network, allowing the payload to be transmitted over to the vulnerable machine (rather than using an isolated NAT, which prevents the packet from synchronizing). 

If you continue to execute the same text file (payload) again, type the command 'rm *shell.elf' to automate deletion, preventing Metasploitable from getting confused with a similar shell.elf text file.

REMINDER: I do not condone any illegal activity, this is merely a basic simulation of Reverse Shell Sniffing using an attacker machine (Kali Linux) sending a malicious payload (shell.elf text file, an empty file used for this exercise) over to a victim/ vulnerable machine (Metasploitable). 
