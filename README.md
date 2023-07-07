# Documenting Security Incidents with an Incident Handler's Journal
This project outlines several unique incidents and shows my comfortability with responding to and documenting the details of Security Events in an Incident Handler's Journal.
While this project covers the overall documentation of several incidents, it is made up of multiple other projects several of which will have their own project repositories. Direct links to these projects will be provided below along with the [Incident Handler's Journal](https://github.com/JacobDKing/IncidentHandlersJournal/blob/main/Incident%20handler's%20journal%20.pdf) itself, which can also be found in this projects main repository.
  - [Analyzing Packet With Wireshark](https://github.com/JacobDKing/AnalyzePacketWithWireshark)
  - [Capturing Packet With TCPdump](https://github.com/JacobDKing/CapturePacketWithTcpdump)
  - [Investigating a Suspicious Hash File]

<br />
<br />

<h1>Scenario #1 (Investigating Ransomware Attack):</h1>
A small U.S. health care clinic specializing in delivering primary-care services experienced a security incident on a Tuesday morning, at approximately 9:00 a.m. Several employees reported that they were unable to use their computers to access files like medical records. Business operations shut down because employees were unable to access the files and software needed to do their job.

Additionally, employees also reported that a ransom note was displayed on their computers. The ransom note stated that all the company's files were encrypted by an organized group of unethical hackers who are known to target organizations in healthcare and transportation industries. In exchange for restoring access to the encrypted files, the ransom note demanded a large sum of money in exchange for the decryption key. 

The attackers were able to gain access into the company's network by using targeted phishing emails, which were sent to several employees of the company. The phishing emails contained a malicious attachment that installed malware on the employee's computer once it was downloaded.

Once the attackers gained access, they deployed their ransomware, which encrypted critical files. The company was unable to access critical patient data, causing major disruptions in their business operations. The company was forced to shut down their computer systems and contact several organizations to report the incident and receive technical assistance.

<br />
<br />

<h1>Scenario #2 (Analyzing Packet With Wireshark):</h1>
In this scenario, you’re a security analyst investigating traffic to a website.

You’ll analyze a network packet capture file that contains traffic data related to a user connecting to an internet site. The ability to filter network traffic using packet sniffers to gather relevant information is an essential skill as a security analyst.

You must filter the data in order to:
  - identify the source and destination IP addresses involved in this web browsing session,
  - examine the protocols that are used when the user makes the connection to the website, and
  - analyze some of the data packets to identify the type of information sent and received by the systems that connect to each other when the network data is captured.

<br />
<br />

<h1>Scenario #3 (Capturing Packet Using TCPDump):</h1>
As a security analyst, it’s important to know how to capture and filter network traffic in a Linux environment. You’ll also need to know the basic concepts associated with network interfaces.

In this lab activity, you’ll perform tasks associated with using tcpdump to capture network traffic. You’ll capture the data in a packet capture (p-cap) file and then examine the contents of the captured packet data to focus on specific types of traffic. 
 
You’re a network analyst who needs to use tcpdump to capture and analyze live network traffic from a Linux virtual machine.
The lab starts with your user account, called analyst, already logged in to a Linux terminal.

<br />
<br />

<h1>Scenario #4 (Investigate a Suspicious File Hash):</h1>
You are a level one security operations center (SOC) analyst at a financial services company. You have received an alert about a suspicious file being downloaded on an employee's computer. 

You investigate this alert and discover that the employee received an email containing an attachment. The attachment was a password-protected spreadsheet file. The spreadsheet's password was provided in the email. The employee downloaded the file, then entered the password to open the file. When the employee opened the file, a malicious payload was then executed on their computer. 

You retrieve the malicious file and create a SHA256 hash of the file. You might recall from a previous course that a hash function is an algorithm that produces a code that can't be decrypted. Hashing is a cryptographic method used to uniquely identify malware, acting as the file's unique fingerprint. 

Now that you have the file hash, you will use VirusTotal to uncover more details about this file.
