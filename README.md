# Detection as Code

## Attachment Interaction

### MITRE ATT&CK

- [T1566.001 - Phishing: Spearphishing Attachment](https://attack.mitre.org/techniques/T1566/001/)

### Instructions

- Line 7

    - Replace the SampleTenantId to your own tenant ID as this is a made-up sender.

- Line 10

    - It can be any extension, but we are looking for PDF attachments in this case.

- Line 12

    - Will depend on your email agent, in this case, Outlook is being used in the environment.

- Line 15

    - Replace the placeholder sender domain in line 15 to the attacker domain (no need to include TLD).

- [Link to Detections AI](https://detections.ai/rules/019bdfb2-48f4-7028-8abc-90875258a4e8)

<p>This KQL script detects if end user interacted with a PDF attachment in a potential phishing/BEC incident.</p>