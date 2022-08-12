# cybersecurity-bootcamp-project3
In this final cybersecurity bootcamp project, our class assignment was to practice offensive and defensive activities, this time going a bit deeper than in Project 2.

As an offensive Red Team, we were tasked with attacking Web Servers running down-rev WordPress software in an Azure virtual network. Our attacks were launched from a Kali VM, and we were encouraged to use nmap, wpscan, hydra, and John the Ripper software, and to upload malware using a reverse shell.

As a defensive Blue Team, we set Kibana alerts which were triggered by the cyberattacks executed by the Red Team, thereby uncovering brute force attacks and the malware upload. Our alerts wrote to log files, but these alerts could just as easily have resulted in emails being sent to SOCs, and mitigating actions being taken.

A third activity had us drill down on packets captured by Wireshark which allowed us to home in on suspicious network behavior, and to detect and isolate ransomware.
The three activities above were completed independently and submitted as homework assignments not included in this repo.

For a fourth activity, we formed teams which drilled down in one of three areas: to execute additional offensive attacks and to be stealthier while doing so; to understand the alerts in more detail and to defensively harden and patch vulnerabilities; and thirdly, to gain a better understanding of what characterizes normal vs. malicious network traffic. 

The team I was on selected to go deeper on defense and “Project 3 - Defense and Hardening Group Presentation.pdf” describes our work. The “Alerts Implemented” section of the report is what I presented on.
