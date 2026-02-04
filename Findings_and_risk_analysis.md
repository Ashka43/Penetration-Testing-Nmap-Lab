# Findings and Risk Analysis

## High-Risk Findings
- Open FTP service allowing anonymous access
- Exposed SMB services
- Multiple unnecessary open ports

## Medium-Risk Findings
- Outdated Apache web server
- Legacy services running on default ports

## Low-Risk Findings
- Informational services with no direct exploit identified

## Risk Impact
The identified vulnerabilities significantly increase the likelihood of:
- Unauthorized access
- Data compromise
- Lateral movement within a network

## Recommendation
- Disable unnecessary services
- Apply regular patching and updates
- Implement firewall rules and network segmentation
