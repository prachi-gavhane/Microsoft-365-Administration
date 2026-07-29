# Microsoft 365 PowerShell

## Overview

PowerShell is a command-line shell and scripting language developed by Microsoft. It enables administrators to automate repetitive tasks, manage Microsoft 365 services, and perform administrative operations that may not be available through the graphical interface.

PowerShell is commonly used to manage Microsoft 365, Exchange Online, Microsoft Entra ID, Microsoft Teams, and SharePoint Online.

---

## Why Use PowerShell?

PowerShell helps administrators to:

- Automate repetitive tasks.
- Perform bulk user management.
- Generate reports.
- Manage Exchange Online.
- Configure Microsoft 365 services.
- Reduce manual administrative effort.

---

## Prerequisites

Before connecting to Microsoft 365 services:

- Install PowerShell 7.x (recommended) or Windows PowerShell 5.1.
- Install the required Microsoft PowerShell modules.
- Use an account with the necessary administrative permissions.

---

## Exchange Online PowerShell

### Install the Module

```powershell
Install-Module ExchangeOnlineManagement
```

### Connect to Exchange Online

```powershell
Connect-ExchangeOnline
```

### Disconnect Session

```powershell
Disconnect-ExchangeOnline
```

---

## Common Administrative Commands

### View Mailboxes

```powershell
Get-EXOMailbox
```

### View Mailbox Statistics

```powershell
Get-EXOMailboxStatistics
```

### Search Unified Audit Log

```powershell
Search-UnifiedAuditLog
```

### View Accepted Domains

```powershell
Get-AcceptedDomain
```

---

## Common Administrative Tasks

PowerShell is commonly used to:

- Connect to Exchange Online.
- Retrieve mailbox information.
- Export administrative reports.
- Search audit logs.
- Perform bulk administrative operations.
- Automate repetitive management tasks.

---

## Real-World Administrative Scenario (Anonymized)

### Requirement

A report of administrative activities was requested for a defined period.

### Administrative Steps

- Connected to Exchange Online PowerShell.
- Verified administrative permissions.
- Executed an audit log search.
- Reviewed the results.
- Exported the required information for analysis.

### Outcome

The requested report was successfully generated and shared with the relevant stakeholders.

---

## Best Practices

- Use PowerShell for repetitive administrative tasks.
- Disconnect Exchange Online sessions after completing work.
- Test scripts in a non-production environment when possible.
- Follow the principle of least privilege.
- Document frequently used commands and scripts.

---

## References

- Microsoft Learn
- Exchange Online PowerShell Documentation
- Microsoft 365 Documentation
