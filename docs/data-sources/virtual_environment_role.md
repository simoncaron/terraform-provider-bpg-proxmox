---
layout: page
title: proxmox_virtual_environment_role
parent: Data Sources
subcategory: Virtual Environment
---

# Data Source: proxmox_virtual_environment_role

Retrieves information about a specific role.

## Example Usage

```hcl
data "proxmox_virtual_environment_role" "operations_role" {
  role_id = "operations"
}
```

## Argument Reference

- `role_id` - (Required) The role identifier.

## Attribute Reference

- `privileges` - The role privileges
