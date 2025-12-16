# Cowrie Honeypot & Canary Token Lab

This repository contains materials for deploying a Cowrie SSH and Telnet honeypot and using canary tokens to detect unauthorized activity. It guides you through setting up the honeypot, monitoring attacker interactions, generating canary tokens, and forwarding logs to a SIEM.

## Overview

You will:
- Deploy a Cowrie honeypot on a Linux host (or container).
- Configure Cowrie to log SSH and Telnet interactions, capturing commands and file downloads.
- Generate canary tokens (e.g., web URL, document token) and place them in the honeypot to detect access.
- Simulate attacker interaction by connecting to the honeypot and triggering the canary tokens.
- Send Cowrie logs and canary alerts to a SIEM such as Splunk or Sentinel for centralized monitoring.
- Write detection queries and build alerts for honeypot hits and canary token activations.
- Document findings and recommend defensive actions.

All data used in this lab is synthetic and controlled; no sensitive information is exposed.
