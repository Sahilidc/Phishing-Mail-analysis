# Phishing-Mail-analysis
A phishing attack is a type of attack that usually aims to steal the user's personal information by tricking them into clicking on malicious links in emails or running malicious files on their computer.

Phishing attacks fall into the  **"Delivery"**  phase of the  **Cyber Kill Chain**  model created to analyze cyber-attacks. The 'delivery' phase is where the attacker transfers the pre-arranged malicious content to the victim systems/people.

	### What does the Email Header do?

  
**Allows you to identify the sender and recipient**  
  

Thanks to the "From" and "To" fields in the header, you can find out who is sending an email and who is receiving it. If we look at the email above, which you have downloaded in "eml" format, we can see that it was sent from "ogunal@letsdefend.io" to "info@letsdefend.io".
## Email Header Analysis
Here are the key questions we need to answer when checking headings during a Phishing analysis:

  
  
-   Was the email sent from the correct SMTP server?
-   Are the data "From" and "Return-Path / Reply-To" the same?

### Static Analysis

Many people find plain text boring, which is why email programs offer HTML support, allowing you to create emails that are more likely to grab the user's attention. Of course, there is a downside to this feature. Attackers can use HTML to create emails that hide malicious URLs behind buttons or text that appear to be harmless.
By querying VirusTotal for web addresses in emails, you can find out if the antivirus engines detect the web address as harmful. If someone else has already analyzed the same address/file in VirusTotal, VirusTotal will not analyze it from scratch, it will show you the old analysis result. This feature can be considered both an advantage and a disadvantage.
## Hands-on-labs
### Lab1
SOC146 - Phishing Mail Detected - Excel 4.0 Macros



### Lab2
  
SOC114 - Malicious Attachment Detected - Phishing Alert
