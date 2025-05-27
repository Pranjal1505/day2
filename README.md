# Objective:
 To Identify phishing characteristics in a suspicious email sample.

# Tools used:
- Mozilla Thunderbird
- MXToolbox
- MAlware- Traffic analysis.net
- Manual inspection

# Steps included in idetification the phishing mail:
- Viewed the email in Thunderbird to check for urgency, attachments and wording.
- Spotted red flags like a ".xz" file and generic message
- Opened full headers and analyzed them using MXToolbox
- Found SPF, DKIM and DMARC failures
- Checked sender IP and found it unauthorized
- Verified the ".xz" file on malware-traffic-analysis.net

# Conclusion
- The email is a clear phishing attempt. It uses spoofed sender info, fake urgency and a malware-loaded attachment. Email authentication failed across the board.

# Recommendations :
•	Do not open such attachments.
•	Always verify the sender via official communication channels.
•	Use email security tools to detect spoofing.
•	Educate employees about phishing indicators.
