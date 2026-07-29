# Exchange Online

## Overview

Exchange Online is Microsoft's cloud-based email and calendaring service included with Microsoft 365. It enables organizations to manage mailboxes, email flow, calendars, contacts, and security without maintaining on-premises Exchange servers.

Exchange Online is administered through the Microsoft 365 Admin Center, Exchange Admin Center (EAC), and Exchange Online PowerShell.

---

## Key Features

- Business email hosting
- Shared mailboxes
- Distribution groups
- Mail flow management
- Calendar sharing
- Anti-spam and anti-malware protection
- Email forwarding
- Mailbox permissions
- Exchange Online PowerShell

---

## Common Administrative Tasks

Microsoft 365 administrators commonly perform:

- Create and manage mailboxes
- Reset mailbox permissions
- Create shared mailboxes
- Manage distribution lists
- Configure mail forwarding
- Manage mail flow rules
- Review message trace
- Connect using Exchange Online PowerShell
- Search audit logs

---

## Exchange Admin Center (EAC)

The Exchange Admin Center is used to manage:

- Mailboxes
- Groups
- Mail flow
- Recipients
- Permissions
- Protection settings
- Reports

---

## Exchange Online PowerShell

PowerShell provides administrators with advanced management capabilities.

### Connect to Exchange Online

```powershell
Connect-ExchangeOnline
```

### Disconnect Session

```powershell
Disconnect-ExchangeOnline
```

Common PowerShell tasks include:

- Managing mailboxes
- Exporting reports
- Viewing mailbox statistics
- Managing permissions
- Performing bulk administrative tasks

---

## Audit Log Search

Administrators can review audit logs to investigate user and administrator activities.

Typical use cases include:

- Mailbox access investigations
- Administrative changes
- User activity tracking
- Compliance reporting

---

## Real-World Administrative Scenario (Anonymized)

### Requirement

An audit report was requested to review activities performed within a Microsoft 365 environment for a specific period.

### Administrative Steps

- Connected to Exchange Online PowerShell.
- Verified the required permissions.
- Executed an audit log search for the requested date range.
- Reviewed the results for relevant administrative activities.
- Exported the report for further analysis.

### Outcome

The requested audit information was successfully retrieved and shared with the relevant stakeholders.

---

## Best Practices

- Use role-based access control (RBAC) for administrative permissions.
- Regularly review mailbox permissions.
- Monitor audit logs periodically.
- Enable Multi-Factor Authentication (MFA) for administrators.
- Use PowerShell for repetitive administrative tasks.

---

## References

- Microsoft Learn
- Exchange Online Documentation
