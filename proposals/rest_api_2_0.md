*Rev*: A &nbsp; &nbsp; *Date*: 11/21/2014

## GOALS for REST API v2.0

- Close the Gap with SOAP API
- Required Enhancements
- Extend Rspecs

### Activities during the REST API 2.0 timeframe:

- ManageIQ/CFME UI Enablement
- ManageIQ/CFME Dev Enablement
- Partner Enhancements/PRs
- Community Enhancements/PRs

___

### Closing the Gap with SOAP API

- Insight Web Services
   - Get Vm Accounts
   - Get Vm Software
- Control Web Services
   - Set Tag on:
      - Cluster
      - Datastore
      - Ems
      - Host
      - Resource Pool
      - Vms
   - Get Policy Action IDs and Names for Policy
   - Add AddLifecycleEvent for VM
   - Assign Policy to Host
   - Unassign Policy from Host
   - Get list of Policy Conditions for Policy
   - Get list of Policy Events for Policy
   - Get list of policies for Host(s)
   - Add a VM Event
   - Add a VM Scan Job
   - SmartStart a VM
   - SmartStop a VM
   - SmartSuspend a VM
   - Delete VM
   - Vm RSOP
   - Add/Delete CustomAttribute(s) to VM
   - Add CustomAttributesByFields to VM
   - Set Owner of VM

---

### Required Enhancements

- Worker independent token manager

---

### Extend Rspecs

- Enable test:requests from test:vmdb
- Extend spec/requests/api

---

### ManageIQ/CFME UI Enablement

- Revamp cfme_client, expose like ActiveModel objects
- Support REST API entry point for co-location environments with UI, i.e. running from source
- Enhancements needed for UI
   - Querying related object attributes
   - Reports Collection

---

### ManageIQ/CFME Dev Enablement

- Enhancements needed for Automation
   - RBAC for /api/automation entrypoint
   - Formal support for zone for automation requests - TBD

---

### Partners

- Query tags as collection i.e. /api/tags
- Get display name for tags when querying
- Creating users
- Creating groups
- Multi-tenant management
- New Collections
   - Network - TBD - Tenant/Visibility Constraint
   - Aws Templates
   - Availability Zones
   - VPC - TBD - Tenant/Visibility Constraint
   - Cloud Subnet - TBD - Tenant/Visibility Constraint
   - Security Groups
- Selecting actions in a running service (same as pushing buttons in UI)
   - Needs to honor RBAC
- Creating Tags & Categories
- Creating providers

---

### Community Enhancements/PRs

---
