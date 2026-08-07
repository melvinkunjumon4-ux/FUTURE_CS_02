# ## Phishing Email Detection & Awareness Report — Cyber Security Task 2, Future Interns

### Overview
An analysis of real-world phishing email samples, performed as part of 
the Cyber Security Internship program at Future Interns. The goal was 
to identify common phishing indicators and translate them into 
plain-language guidance suitable for non-technical users.

### Sample Source
- 7 phishing email samples sourced from rf-peixoto/phishing_pot, a 
public, actively maintained archive of real collected phishing emails 
used for research and education

### Tools Used
- **Email header analysis** — manual inspection of Authentication-Results 
(SPF, DKIM, DMARC), Received chain, and Reply-To fields
- **Browser tools** — used to safely inspect link destinations without 
clicking them

### Analysis Approach
Each sample was examined at two levels:
1. **Header level** — sender authentication results, true originating 
server, and Reply-To mismatches
2. **Content level** — subject line framing, urgency/manipulation 
language, and embedded link destinations

No emails were opened in a live mail client, no links were clicked, and 
no attachments were downloaded during analysis.

### Findings Summary
All 7 samples were classified as Phishing, spanning multiple attack 
types: bank/brand impersonation, advance-fee scams, prize/reward scams, 
disguised-link spam, and a cryptocurrency airdrop scam. Full details, 
red flags, and classifications for each sample are documented in the 
report.

### Files in This Repository
- CYBERSECURITY-TASK-2.pdf — full Phishing Detection & Awareness Report
- CYBER_TASK2_Evidence.pdf — evidence document containing analyzed 
email header screenshots

### Deliverable
This report was designed to serve as employee-facing security awareness 
material — helping non-technical readers recognize phishing patterns 
without needing a technical security background.
