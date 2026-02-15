# Email Header Analysis

## Tool Used
MXToolbox Header Analyzer (or any free online header analyzer)

---

## Findings

### 1. Originating Server
The IP address does not belong to the official PayPal mail servers.

### 2. SPF Check
SPF validation failed, indicating the sender is not authorized to send emails on behalf of the domain.

### 3. DKIM Authentication
DKIM signature was missing or invalid, reducing the credibility of the email.

### 4. Reply-To Mismatch
The reply-to address differed from the sender address, which is a strong phishing indicator.

---

## Verdict
The header inconsistencies strongly suggest that the email was sent from an unauthorized source.
