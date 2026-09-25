# DNS Enumeration

## A Records
- meditech-solutions.example → 192.168.10.20

## MX Records
- mail.meditech-solutions.example → priority 10

## TXT Records
- "v=spf1 include:_spf.google.com ~all"

## Observations
- SPF record allows Google Workspace mail servers.
- No DMARC record found.
- MX server exposed externally.

## Risks
- Missing DMARC increases spoofing risk.
- Exposed mail server may reveal software versions.
