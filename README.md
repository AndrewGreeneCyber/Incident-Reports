<h1>Analyzing Network Structure and security</h1>


<h2>Description</h2>
This project analyzed DNS and ICMP traffic logs to investigate repeated failed DNS queries to the server 203.0.113.2, which prevented resolving the domain www.yummyrecipesforme.com. The incident was traced to ICMP messages indicating "udp port 53 unreachable," suggesting potential misconfiguration, service outage, or firewall blocks on the DNS server. Recommendations included verifying DNS server configuration, reviewing firewall rules, investigating potential Denial of Service (DoS) attacks, and establishing backup DNS servers to ensure reliable domain name resolution. By addressing these issues, access to the website can be restored for users.
<br />


<h2>Summary, analysis, and next steps:</h2>

<p align="center">
<br/>
<img src="https://imgur.com/C0Rxr3T.png" height="80%" width="80%" 
<br />
<br/>
<img src="https://imgur.com/XiHcF30.png" height="80%" width="80%" 
<br />

<!-- Add the button at the bottom -->
<div style="text-align: center; margin-top: 20px;">
    <a href="https://github.com/AndrewGreeneCyber" target="_blank" style="text-decoration: none;">
        <button style="background-color: #007BFF; color: white; padding: 10px 20px; border: none; border-radius: 5px; font-size: 16px; cursor: pointer;">
            Visit Homepage
        </button>
    </a>
</div>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
