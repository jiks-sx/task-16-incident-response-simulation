# Incident Response Simulation Lab

## Step 1: Simulate Incident
Generate multiple failed login attempts (lab environment).



## Step 2: Identify Suspicious Activity
Check authentication logs:

- sudo grep "Failed password" /var/log/auth.log

Identify repeated login attempts from the same IP.


## Step 3: Classify Incident
Example:

- Attack Type → Brute Force
- Severity → Medium / High



## Step 4: Containment
Block attacker IP:

- sudo ufw deny from 192.168.1.50



## Step 5: Eradication
Reset compromised passwords and remove unauthorized accounts.



## Step 6: Recovery
Verify system integrity and restore normal operations.



## Step 7: Documentation
Record:
- Incident time
- Affected systems
- Actions taken
- Remediation steps
