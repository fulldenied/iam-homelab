# Active Directory Basics – Tasks 6–8 (TryHackMe)
*Completed: Nov 4, 2026*

## Group Policy Objects (GPOs)
- GPOs are linked to OUs and apply their settings to the users and computers inside that OU.
- This makes it easier to manage settings consistently for each OU.
- `gpupdate /force` applies GPO changes on a machine right away.

## Kerberos
- Kerberos is the current default authentication protocol in Windows domains.
- It is ticket-based: when a user logs in, they receive a TGT (Ticket Granting Ticket).
- The TGT is used to request tickets for each service, so credentials don't have to be sent again.

## Trees and forests
- A tree is a group of domains that share the same namespace (e.g., one company with a domain for each country or location).
- A forest is a group of trees with different namespaces.

## Trusts
- A trust relationship lets users from one domain access certain resources in another domain.
- One-way trust: if Domain A trusts Domain B, users in B can access resources in A.
- Two-way trust: users in both domains can access resources in the other.
