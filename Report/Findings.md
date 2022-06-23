## Reconnaissance 

Using *nmap* ping sweep capabilities a network topology was encountered with the following characteristics:

##### CHART

This report will involve further investigation into the security of the Target 1 machine at 192.168.1.110.

A SYN scan on Target 1 revealed a website on port 80 and an rpc service on port 111, among other services.

To learn more about the website a *dirb* scan was conducted. This revealed a wordpress service:

A *wpscan* was used to gather more information on the wordpress service. 
This revealed several usernames: 






 

