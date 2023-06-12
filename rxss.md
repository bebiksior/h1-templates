## Title: 
Reflected XSS in {URL}

## Description
I found Reflected Cross-Site Scripting vulnerability. The application does not properly sanitize user input in the {PARAM_NAME} parameter, leading to an XSS vulnerability. This vulnerability can be exploited by sending a crafted URL with malicious JavaScript to a victim.

## Steps to Reproduce:
1. Navigate to {URL}.
2. An alert box will appear, demonstrating the vulnerability.

## Impact:
An attacker can execute arbitrary JavaScript in the victim's browser, leading to stealing victim cookies, redirecting to phising website.
