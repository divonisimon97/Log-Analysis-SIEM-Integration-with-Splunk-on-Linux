# Log-Analysis-SIEM-Integration-with-Splunk-on-Linux

<h2>Description</h2>
In this project, I set up Splunk on Linux to collect, analyze, and monitor system logs (syslog, authentication logs, and system events) for IT support and security purposes.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Terminal </b>

<h2>Environments Used </h2>

- <b>Linux</b> (6.11.2)

<h2>Program walk-through:</h2>

<p align="center">
Download & Install Splunk: <br/>
<img src="https://i.imgur.com/wDNI5vG.png" width="80%" alt="Creating a MD5-crypt hash"/>
<img src="https://i.imgur.com/K3ZtG9X.png" width="80%" alt="Creating a MD5-crypt hash"/>
<img src="https://i.imgur.com/0m2zA35.png" width="80%" alt="Creating a MD5-crypt hash"/>
<br />
<br />
Receive Web Interface: <br/>
<img src="https://i.imgur.com/NC2veVq.png" height="80%" width="80%" alt="Creating a MD5-crypt hash"/>
<br />
<br />
Log-In Web Interface: <br/>
<img src="https://i.imgur.com/OkGUD9O.png" height="80%" width="80%" alt="Creating a MD5-crypt hash"/>
<br />
<br />
Open the rsyslog configuration file: <br/>
<img src="https://i.imgur.com/eT2RvUu.png" height="80%" width="80%" alt="Creating a MD5-crypt hash"/>
<br />
<br />
Add a Forwarding Rule: <br/>
<img src="https://i.imgur.com/QAANRCq.png" height="80%" width="80%" alt="Creating a MD5-crypt hash"/>
<br />
<br />
Add a Rule to Write to /var/log/syslog: <br/>
<img src="https://i.imgur.com/9lQoZpe.png" height="80%" width="80%" alt="Creating a MD5-crypt hash"/>
<br />
<br />
Create the Log File, Set Appropriate Permissions, then Restart: <br/>
<img src="https://i.imgur.com/bsxg8DC.png" height="80%" width="80%" alt="Creating a MD5-crypt hash"/>


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
