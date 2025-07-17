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
| **Identify the network protocol involved in the incident** | The network protocols involved in the incident are **DNS** and **HTTP**. The DNS protocol was used for the source computer to send a DNS query to the server `dns.google.domain`. The HTTP protocol was used for the communication between the source computer and `yummyrecipesforme.com.http`. |

| Section 2 | Details |
|---------|---------|
| **Identify the network protocol involved in the incident** | In a recent cybersecurity incident, ‘yummyrecipeforme.com’ was the target of a successful brute force attack initiated by a formal employee. The attacker attempted multiple default administrator passwords until they successfully gained unauthorized access to the website’s backend.<br>Once access was obtained, the attacker injected malicious JavaScript into the website. This code altered the website to where it would automatically download an executable file onto user’s devices. When executed, the script would redirect users to a phony website called ‘greatrecipesforme.com’.<br>As a result, users who ran the file experienced suspicious behavior on their systems and may require IT support due to potential malware infection. 
 |
