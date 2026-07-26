# Windows Event Logs

## Important Event IDs

| Event ID | Description |
|----------|-------------|
| 4624 | Successful Logon |
| 4625 | Failed Logon |
| 4688 | Process Creation |
| 4672 | Special Privileges Assigned |
| 4720 | User Account Created |

## Detection Example

Detect brute-force attacks by identifying multiple Event ID 4625 entries followed by Event ID 4624.
