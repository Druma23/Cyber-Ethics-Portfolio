# My First-Hour Priorities: 
### Capture:
Recording custody rows as you go. This ensures accuracy and is more efficient. 
Minimal targeted evidence. Protects privacy, lowers the risk, and keeps evidence defensible. 
### Avoid:
Writing accusations. Could hurt the Incident note, by not keeping it factual. 
Using ongoing monitoring to try and prove something. It would take too long and distract you from finding what you need.
## Incident & Evidence Note: 
Incident # HC-IR-1066
### • Timestamp (UTC) & Context: 2025-09-11T13:45:00Z notified by student Sam Rivera that an unauthenticated email message was sent to him. Ticket created.
### • Authorization: Incident manager John Smith approved inspections on IdP logs for 15 minutes before and after the suspicious email was received. No other assets authorized. 
### • Actions Taken: 13:50Z — Exported the reported message as raw .eml 
• 13:52Z — Exported IdP sign-in events for sam.rivera within the approved window of 15 minutes before/after unauthenticated email received. 
• 13:54Z — Chain of custody and evidence recorded. 
• 13:55Z — SHA-256 for both artifacts calculated
• 14:00Z — Completed analysis; Soft containment is the prepared recommendation.
### • Evidence Captured: Item ID: EV 001  Phishing email (.eml; headers+body) — SHA-256: b2e70976a832a7a5c1ef979042a3cdac4cbea710dbcd0e69eb405f2d258c2346  Why: Shows DMARC alignment failure and shows SPF softfail
Item ID: EV 002 IdP Logs — SHA-256: c52df5aa4ff5507ecf844a98edd42309d4266f41747bd09264b79f6047320769 Why: Shows password and MFA successes/failures for 15 minutes before and after unauthenticated email
### • Chain of Custody: Stored at Safe Location; automatically logged; transfer records kept.
### • Redaction: Removed all other users information except for Sam Rivera; using Blur method
### Next Step: Recommend Soft Containment- disable account, password reset, monitor for another 48 hours and handoff to Incident Manager John Smith.
## Integrity & Privacy Controls: 
Hashing is a cryptographic identifier of files and helps the integrity of a file. It does this by helping to prevent any tampering with the file. An example of hashing is SHA-256. A good storage location for data would be in a secure location with access only being granted to individuals that have approved authorization. Along with this an understandable redaction policy needs to be in place. The redaction policy needs to include the removal or blurring of PII. The combination of the tools listed above help create a trustable incident report handling. All of this helps with the compliance of HIPAA and a feminist ethical framework by showing integrity with the data given. 
Evidence Links: 
Incident & Evidence Note 
Incident Ethics & Evidence Notes 

## Reflection:
Next time I would like to divulge deeper into the last Success Sam.rivera’s account had. The first successful result Sam was using Windows 11 at Campus-NAT with IP 198.51.60.10 . Whereas, the last successful result was using Linux at VPN exit (commercial) with IP 203.0.113.175 and that IP matches the previous fails. This would make me think the phishers got into Sam’s account and more action would need to be taken. 

## AI Use Note:
I used SAGE to help me study the material. I also used SAGE to proofread and give me feedback on my What I Learned summary
