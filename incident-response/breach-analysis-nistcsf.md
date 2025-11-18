# Breach Analysis (Capital One Style) – NIST CSF Mapping

## Summary
A WAF misconfiguration allowed an attacker to exploit an SSRF vulnerability and access an AWS S3 bucket containing customer PII.

## What Failed
- IAM policies were overly permissive  
- Monitoring alerts were not integrated with SIEM  
- No cloud-specific incident playbooks  

## NIST CSF Mapping
**Identify:** Missing cloud asset inventory  
**Protect:** Weak IAM & misconfigured S3 bucket  
**Detect:** No anomaly alerting for data exfiltration  
**Respond:** Delayed incident handling  
**Recover:** No formal lessons-learned review

## Lessons for Nova
- Enforce least-privilege IAM  
- Integrate GuardDuty → SIEM  
- Implement cloud configuration monitoring  
- Build cloud incident runbooks  
