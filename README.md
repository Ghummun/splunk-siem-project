# Splunk SIEM Security Monitoring Project

## 📋 Project Overview
Hands-on deployment and configuration of Splunk Enterprise SIEM for security log analysis and threat monitoring. This project demonstrates practical experience with enterprise security tools used in Security Operations Centers (SOCs).

## 🎯 Objectives
- Deploy and configure Splunk Enterprise locally
- Gain hands-on experience with SIEM operations
- Practice security log analysis and threat detection
- Understand security dashboard creation and monitoring

## 🛠️ Technical Implementation

### 1. Splunk Deployment
- Downloaded and installed Splunk Enterprise 9.x (Free Edition)
- Configured local instance with admin access
- Verified successful installation and web interface access

### 2. Security Log Analysis
- Accessed Splunk's built-in `_internal` index containing system logs
- Created SPL (Search Processing Language) queries to analyze security events:
  ```spl
  index=_internal (error OR failed OR denied) | head 20
