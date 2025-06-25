# Phishing Email Analysis 

## Objective
To identify and document phishing indicators in a suspicious email using an email header analyzer and manual inspection techniques.

## Tools Used
- Gmail (to access and inspect the email)
- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- Notepad (for writing the report)

## What I Did

1. **Obtained a suspicious email sample**:  
   - Used a simulated phishing email with a subject like:  
     _"Urgent: Account Suspended Due to Billing Failure"_

2. **Inspected the email in Gmail**:  
   - Viewed the full sender email and checked for domain spoofing.  
   - Clicked "Show Original" to get full headers.

3. **Analyzed the headers**:  
   - Pasted headers into MXToolbox.  
   - Identified SPF/DKIM status.

4. **Identified phishing indicators**:  
   - Fake sender address  
   - Suspicious link   
   - Urgent language    
   - Generic greeting and minor grammar errors

5. **Created a phishing report**:  
   - Summarized all phishing traits found  

