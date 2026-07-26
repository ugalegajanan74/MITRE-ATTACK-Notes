# T1110 - Brute Force

## MITRE ID
T1110

## Tactic
Credential Access

## Description
Brute Force is a technique where an attacker repeatedly tries different username and password combinations to gain unauthorized access.

## Indicators

- Multiple failed login attempts
- Successful login after repeated failures
- Login attempts from the same IP address

## Windows Event IDs

- 4625 – Failed Logon
- 4624 – Successful Logon

## Detection

- Monitor repeated failed login attempts.
- Detect a successful login after many failures.
- Correlate authentication events in a SIEM.

## Prevention

- Enable Multi-Factor Authentication (MFA)
- Configure account lockout policies
- Use strong passwords
- Monitor authentication logs
