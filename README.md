# [Phishing Emails Alert Playbook](#phishing-emails-alert-playbook)

## Steps

1. **Initial Triage**  
   - Verify the alert and gather basic information:
     - Sender
     - Recipient
     - Timestamp
     - Subject line

2. **Email Analysis**  
   - Examine the email headers, body content, and attachments for signs of phishing.

3. **URL Analysis**  
   - Check embedded links using URL reputation services.

4. **Attachment Analysis**  
   - Analyze attachments in a sandbox environment.

5. **User Interaction**  
   - Contact the recipient to determine if any action was taken.

6. **Containment**  
   - Block the sender's email address and domain.  
   - Isolate affected systems.

7. **Remediation**  
   - Educate the user on recognizing phishing attempts.  
   - Update email filters to prevent similar attacks.

## Reputation Check Tools

- [VirusTotal](https://www.virustotal.com)  
- [URLVoid](http://www.urlvoid.com/)
