# T1110 - Brute Force

## Tactic

Credential Access

## Description

Attackers try multiple username and password combinations to gain unauthorized access.

## Indicators

- Multiple failed login attempts
- Successful login after repeated failures
- Login attempts from a single IP

## Windows Event IDs

- 4625
- 4624

## Detection

- Monitor repeated failed logins.
- Alert on multiple failures followed by a success.
- Correlate events using SIEM.

## Prevention

- Enable MFA
- Use account lockout policies
- Strong passwords
- Monitor authentication logs
