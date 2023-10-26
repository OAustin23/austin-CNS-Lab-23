# Orwin Austin [CNS Homework #7/ 26 OCT 2023]

## Question #2
### "My research began with a 'Metasploit "search cve"' command in the `msfconsole` on my Kali Linux virtual machine (VM). This phase entailed scanning for CVEs and identifying unpatched software versions susceptible to the discovered exploits. This step proved to be the most challenging, often necessitating several discussions with the instructor before arriving at a decision.
Initially, I focused on a WordPress plugin vulnerable to SQL injection, but locating the corresponding software version proved elusive. I subsequently shifted my attention to an older version of Google. However, akin to the WordPress vulnerability, pinpointing the software version felt like searching for a needle in a haystack.
As I became more proficient in the search process and discovered new tools, I stumbled upon the Netgate pfSense vulnerability, which captured my interest, as this is the firewall software we employ. I extensively scoured the internet to find a version earlier than v2.7.0 for the service, and fortunately, I located one after a few hours of searching. This discovery was nestled within a GitHub repository that thoughtfully outlined the steps to execute the exploit."



## Question #3
### The CVE ID for this vulnerability is CVE-2023-27253, and its CWE ID is CWE-91. In XML, special elements encompass reserved words or characters like "<", ">", """, and "&," which can be leveraged to insert new data or alter XML syntax. The exploit functions by executing an authenticated command injection, enabling an authenticated attacker with the 'WebCfg - Diagnostics: Backup & Restore' privilege to run arbitrary OS commands as the 'root' user.


## References

### https://nvd.nist.gov/vuln/detail/CVE-2023-27253#toggleConfig1
### https://packetstormsecurity.com/files/173487/pfSense-Restore-RRD-Data-Command-Injection.html
### https://github.com/advisories/GHSA-mh3m-qv7g-hjvv



