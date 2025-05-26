Objective: To perform certain attacks on the vulnerabilities using nmap

explanation for nmap.pdf:
We have an attacker and victim namely kali and metasploitable. Here the metasploitable is a very vulnerable framework. The first step is to create a file in meta. Note the meta must be running in order to find the open port. In kali we use Nikto ( open-source web server vulnerability scanner used to identify security issues in web servers and web applications). Here changing to super user is necessary for privledges and when the nmap is used with -sS -Sv meta Ip we get connected to the the port. This sort of connection can be used for vulnerability testing. The kali and access meta(victim) and perform backdoor attack and get the relevant information that includes deleting existing files and creating new files. This compromises the confidentiality and integrity of the files present in the victim system. This type of scanning is used for discovering vulnerable open ports in platforms and not a single link or URL.


Conclusion:
NMAP is a powewrful tool used for finding open ports in any network and to find various vulnerabilties present in the platforms. 


Additional:
Types of attacks that can be performed:
1.Backdoor: These are malicious or hidden ways into a system, often left by malware or attackers.
nmap -sV -p 31337 192.168.1.5

2.Vulnerable Services: Outdated or misconfigured services that are known to be vulnerable to remote code execution or privilege escalation.
nmap -sV --version-light target_ip

3.Trojan Horses / Remote Access Trojans (RATs): Malicious programs that open secret communication channels

4.Default or Open Ports: Login pages or tools left exposed.
