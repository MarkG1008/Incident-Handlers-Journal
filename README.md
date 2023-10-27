# Incident Handler's Journal


<table>
  <tr>
   <td><strong>Date:</strong> August 23, 2023
   </td>
   <td colspan="3" ><strong>Entry: </strong>
<p>
#1
   </td>
  </tr>
  <tr>
   <td>Description
   </td>
   <td colspan="3" >Documenting a cybersecurity incident 
<p>
This incident occurred in two phases: 
<ol>

<li><strong>Detection and Analysis</strong>: The scenario outlines how the organization first detected the ransomware incident. For the analysis step, the organization contacted several organizations for technical assistance.

<li><strong>Containment, Eradication, and Recovery</strong>: The scenario details some steps that the organization took to contain the incident. For example, the company shut down their computer systems. However, since they could not work to eradicate and recover from the incident alone, they contacted several other organizations for assistance.
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>Tool(s) used
   </td>
   <td colspan="3" >None
   </td>
  </tr>
  <tr>
   <td>The 5 W's 
   </td>
   <td colspan="3" >
<ul>

<li><strong>Who</strong>: An organized group of unethical hackers

<li><strong>What</strong>: A ransomware security incident

<li><strong>Where</strong>: At a healthcare company

<li><strong>When</strong>: Tuesday 9:00 a.m.

<li><strong>Why</strong>: The incident happened because unethical hackers were able to access the company's systems using a phishing attack. After gaining access, the attackers launched their ransomware on the company's systems, encrypting critical files. The attackers' motivation appears to be financial because the ransom note they left demanded a large sum of money in exchange for the decryption key.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Additional notes
   </td>
   <td colspan="3" >
<ol>

<li>How could the healthcare company prevent an incident like this from occurring again?

<li>Should the company pay the ransom to retrieve the decryption key?
</li>
</ol>
   </td>
  </tr>
</table>



---


<table>
  <tr>
   <td><strong>Date:</strong> August 23, 2023
   </td>
   <td colspan="3" ><strong>Entry: 
</strong> <p></p> #2
   </td>
  </tr>
  <tr>
   <td>Description
   </td>
   <td colspan="3" >Analyzing a packet capture file 
   </td>
  </tr>
  <tr>
   <td>Tool(s) used
   </td>
   <td colspan="3" >For this activity, I used Wireshark to analyze a packet capture file. Wireshark is a network protocol analyzer that uses a graphical user interface. The value of Wireshark in cybersecurity is that it allows security analysts to capture and analyze network traffic. This can help in detecting and investigating malicious activity.
   </td>
  </tr>
  <tr>
   <td>The 5 W's
   </td>
   <td colspan="3" >
<ul>

<li><strong>Who</strong>: N/A

<li><strong>What</strong>: N/A

<li><strong>Where</strong>: N/A

<li><strong>When</strong>: N/A

<li><strong>Why</strong>: N/A
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Additional notes
   </td>
   <td colspan="3" >I've never used Wireshark before, so I was excited to begin this exercise and analyze a packet capture file. At first glance, the interface was very overwhelming. I can see why it's such a powerful tool for understanding network traffic.
   </td>
  </tr>
</table>



---


<table>
  <tr>
   <td><strong>Date:</strong> August 24, 2023
   </td>
   <td colspan="3" ><strong>Entry:</strong>
<p>
#3
   </td>
  </tr>
  <tr>
   <td>Description
   </td>
   <td colspan="3" >Capturing my first packet
   </td>
  </tr>
  <tr>
   <td>Tool(s) used
   </td>
   <td colspan="3" >For this activity, I used tcpdump to capture and analyze network traffic. Tcpdump is a network protocol analyzer that's accessed using the command-line interface. Similar to Wireshark, the value of tcpdump in cybersecurity is that it allows security analysts to capture, filter, and analyze network traffic. 
   </td>
  </tr>
  <tr>
   <td>The 5 W's
   </td>
   <td colspan="3" >
<ul>

<li><strong>Who</strong>: N/A

<li><strong>What</strong>: N/A

<li><strong>Where</strong>: N/A

<li><strong>When</strong>: N/A

<li><strong>Why</strong>: N/A
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Additional notes
   </td>
   <td colspan="3" >I'm still new to using the command-line interface, so using it to capture and filter network traffic was a challenge. I got stuck a couple of times because I used the wrong commands. However, after carefully following the instructions and redoing some steps, I was able to get through this activity and capture network traffic.
   </td>
  </tr>
</table>



---


<table>
  <tr>
   <td><strong>Date:</strong> August 24, 2023
   </td>
   <td colspan="3" ><strong>Entry:</strong>
<p>
#4
   </td>
  </tr>
  <tr>
   <td>Description
   </td>
   <td colspan="3" >Investigate a suspicious file hash
   </td>
  </tr>
  <tr>
   <td>Tool(s) used
   </td>
   <td colspan="3" >For this activity, I used VirusTotal, which is an investigative tool that analyzes files and URLs for malicious content such as viruses, worms, trojans, and more.  It's a very helpful tool to use if you want to quickly check if an indicator of compromise like a website or file has been reported as malicious by others in the cybersecurity community. For this activity, I used VirusTotal to analyze a file hash, which was reported as malicious. 
<p>
This incident occurred in the <strong>Detection and Analysis</strong> phase. The scenario put me in the place of a security analyst at a SOC investigating a suspicious file hash. After the suspicious file was detected by the security systems in place, I had to perform deeper analysis and investigation to determine if the alert signified a real threat. 
   </td>
  </tr>
  <tr>
   <td>The 5 W's
   </td>
   <td colspan="3" >
<ul>

<li><strong>Who</strong>: An unknown malicious actor 

<li><strong>What</strong>: An email sent to an employee contained a malicious file attachment with the SHA-256 file hash of 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

<li><strong>Where</strong>: An employee's computer at a financial services company

<li><strong>When</strong>: At 1:20 p.m., an alert was sent to the organization's SOC after the intrusion detection system detected the file

<li><strong>Why</strong>: An employee was able to download and execute a malicious file attachment via e-mail.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Additional notes
   </td>
   <td colspan="3" >How can this incident be prevented in the future? Should we consider improving security awareness training so that employees are careful with what they click on? 
   </td>
  </tr>
</table>
