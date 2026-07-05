Email Header Analysis & Mail Tracking Detection Tool

Overview:
A Python-based security tool that parses raw email 
headers to detect phishing indicators, email 
spoofing, and malicious tracking links. Built as 
part of SOC analyst portfolio to demonstrate 
practical email forensics skills.

What This Tool Does:
- Extracts sender originating IP address from 
  raw email headers
- Checks SPF, DKIM, and DMARC authentication 
  results to detect spoofed emails
- Identifies tracking links and redirect URLs 
  embedded in phishing and marketing emails
- Generates a structured human-readable security 
  report from raw header input
Technologies Used:
- Python
- Regex (Regular Expressions)
- Email authentication protocols — SPF, DKIM, DMARC

SOC Relevance:
Phishing is the #1 attack vector investigated 
by Tier 1 SOC analysts. This tool simulates the 
email header investigation workflow a SOC analyst 
follows when triaging a suspicious email alert.

Skills Demonstrated:
- Python scripting for security automation
- Email forensics and header analysis
- SPF/DKIM/DMARC authentication understanding
- Phishing detection methodology
- Structured security report writing

