# Phishing Email Analysis Report

## Overview
This report analyzes a suspicious email to identify phishing characteristics commonly used by attackers to trick recipients into revealing sensitive information.

---

## Sender Analysis
The sender email address appears legitimate at first glance but contains a spoofed domain:

**support@paypaI.com**

The lowercase letter "L" in PayPal is replaced with an uppercase "I", which is a common phishing technique.

---

## Email Content Review
The email warns that the recipient’s account will be suspended within 24 hours unless immediate action is taken. Such urgency is frequently used in phishing attacks to pressure victims.

Additionally, the greeting "Dear Customer" indicates mass distribution rather than a personalized message.

---

## Link Inspection
The email contains a verification link:

http://paypal.verify-user-account-security.com

This domain is not officially associated with PayPal and likely redirects users to a fake login page designed to steal credentials.

---

## Header Examination
Header analysis revealed that the email originated from a server unrelated to PayPal.

Authentication checks such as SPF and DKIM were either missing or failed, further confirming the email is not legitimate.

---

## Conclusion
Based on the spoofed sender address, suspicious link, urgent language, and header discrepancies, this email is highly likely to be a phishing attempt.
