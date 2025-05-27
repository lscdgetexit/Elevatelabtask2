> ### Task 2: Analyze a Phishing Email Sample.

> ### Objective: Identify phishing characteristics in a suspicious email sample.

> ### Key Concepts: Phishing, email spoofing, header analysis, social engineering, threat detection

-----------------------------------------------------------------------------------

![image](https://github.com/user-attachments/assets/c3847cfa-9e27-4798-9f54-f784b36b3d23)

# Phishing Email Analysis Report

  Sample Email Details

- **Subject**: High-severity alert: Phish delivered due to tenant or user override  
- **Sender Address**: microsoft@email-records.com  
- **Claimed Sender**: Microsoft / Office 365  
- **Screenshot**: See attached image above

 ## Phishing Indicators Identified

a. Spoofed Sender Address

>> The email claims to be from Microsoft but is sent from microsoft@email-records.com, which is not a legitimate Microsoft domain.

b. Generic Branding Abuse

>> Microsoft and Office 365 logos are present, but can easily be copied and reused by attackers.

c. Urgent Language

>> The phrase “A high-severity alert has been triggered” is designed to instill panic and urgency, manipulating the user into clicking without thinking.

d. Suspicious Link

>> The "View alert details" button likely redirects to a malicious site. Hovering over it (not clicking!) would typically reveal a mismatched or fake URL.

e. Unusual Formatting

>> Inconsistent spacing and formatting: e.g., “sent by Unknown to at time…” looks suspicious and not professionally formatted.

f. Technical Jargon to Confuse

>> Phrases like 2aec-43aa-a943-08d7333445ae-1065783939474734-1 are inserted to appear technical or authentic but serve no real informational purpose.

##  Tools Recommended for Header Analysis
- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- Gmail’s "Show original" header view
- Built-in email client header tools

##  Why This Email Is Dangerous
- Links may lead to credential harvesting pages or malware downloads.
- The branding is used to exploit user trust in Microsoft.
- It is an example of **social engineering** using fear and authority.

##  Actions to Take
- **Do not click** on suspicious links.
- Report the email as phishing in your mail client.
- Check email headers and link targets.
- Block the sender and notify IT/security team if on a corporate network.

