# Emerging Threats / Campaigns
 
Sigma rules for active, time-sensitive threats — newly disclosed vulnerabilities,
in-the-wild exploit chains, and tracked campaigns.
 
## Conventions
 
- One campaign/threat per subdirectory.
- Standard Sigma filenames (`<logsource>_<platform>_<description>.yml`).
- Each rule carries `references` to the source disclosure or advisory.
- Baseline and validate before enabling in production — check each rule's deployment
  notes for required logsources and false-positive guidance.
 