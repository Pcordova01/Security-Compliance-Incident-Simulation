# Scenario 2: Cybersecurity Incident Report

## Scenario
You work as a security analyst for a travel agency that advertises sales and promotions on the company’s website. The employees of the company regularly access the company’s sales webpage to search for vacation packages their customers might like. 

One afternoon, you receive an automated alert from your monitoring system indicating a problem with the web server. You attempt to visit the company’s website, but you receive a connection timeout error message in your browser.

You use a packet sniffer to capture data packets in transit to and from the web server. You notice a large number of TCP SYN requests coming from an unfamiliar IP address. The web server appears to be overwhelmed by the volume of incoming traffic and is losing its ability to respond to the abnormally large number of SYN requests. You suspect the server is under attack by a malicious actor. 

You take the server offline temporarily so that the machine can recover and return to a normal operating status. You also configure the company’s firewall to block the IP address that was sending the abnormal number of SYN requests. You know that your IP blocking solution won’t last long, as an attacker can spoof other IP addresses to get around this block. You need to alert your manager about this problem quickly and discuss the next steps to stop this attacker and prevent this problem from happening again. You will need to be prepared to tell your boss about the type of attack you discovered and how it was affecting the web server and employees.

## Wireshark TCP/HTTP Log
![Screenshot 2025-07-17 172257](https://github.com/user-attachments/assets/5cd28656-89a6-45d4-a60c-b5f6ddbf9b70)

## Security Incident Report
| Section 1 | Details |
|---------|---------|
| **Identify the network protocol involved in the incident** | The primary network protocol involved is TCP. The attack used TCP SYN requests to initiate half-open connections in large volume, overwhelming the web server’s ability to respond. This caused connection timeouts for users attempting to reach the company website.|

| Section 2 | Details |
|---------|---------|
| **Document the Incident** | A Denial-of-Service (DoS) attack was launched against the company’s web server using a SYN flood technique. This was characterized by a surge in incoming TCP SYN requests from a suspicious IP address. The server’s resources became exhausted as it attempted to respond to each request, eventually becoming unresponsive. This disruption impacted internal employees and potentially external customers. As an immediate response, the server was taken offline and the offending IP address was blocked via firewall rules. However, further steps are needed to protect against future attempts that may use different IPs or more sophisticated methods. |
 

| Section 3 | Details |
|---------|---------|
| **Recommend one remediation for brute force attacks** | 	To prevent SYN flood attacks, it is recommended to implement SYN cookies or connection limiting at the firewall or web server level. SYN cookies help prevent the server from allocating resources until the handshake is complete. Additionally, consider deploying a Web Application Firewall (WAF) or using a DDoS protection service (e.g., Cloudflare, AWS Shield) that can detect and mitigate flood-based attacks in real time. Intrusion Detection Systems (IDS) can also be configured to alert security teams of unusual SYN traffic patterns.|
