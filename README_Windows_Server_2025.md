# Windows Server 2025 --- System Administration & Infrastructure Security

**Author:** Pedro Gonçalves\
**Project type:** Hands-on virtual infrastructure laboratory\
**Documentation language:** Portuguese\
**Focus:** Windows Server administration, identity, networking, storage,
access control, and infrastructure resilience.

## Overview

This portfolio documents the configuration and administration of a
Windows Server 2025 lab with a Windows 11 client. It combines
step-by-step explanations, screenshots, command-line examples, and
validation activities. The report covers installation, service
deployment, troubleshooting, and security-oriented administration.

> **Scope note:** This is an educational lab portfolio. Documented
> procedures and screenshots should not be interpreted as production
> deployments or independently verified security assessments.

## Laboratory environment

-   **Server:** Windows Server 2025
-   **Client:** Windows 11
-   **Virtualization:** Oracle VirtualBox
-   **Administration:** Server Manager, Windows Admin Center /
    administrative consoles, PowerShell, CMD, Remote Desktop
-   **Identity and network services:** Active Directory Domain Services
    (AD DS), DNS, DHCP, Group Policy

## Topics covered

  -----------------------------------------------------------------------
  Area                                Practical work documented
  ----------------------------------- -----------------------------------
  Deployment                          Windows Server installation,
                                      virtual machines, server and client
                                      setup

  Storage                             Storage pools, virtual disks,
                                      volumes, expansion and file
                                      services

  Networking                          Static IP configuration, NIC
                                      teaming, connectivity tests and
                                      troubleshooting

  PowerShell                          Network adapter inspection, IP
                                      configuration, DNS cache, routes,
                                      diagnostics

  Active Directory                    Domain controller promotion, domain
                                      join, user and group management

  DNS                                 Forward and reverse lookup, host
                                      records, client configuration,
                                      service administration

  DHCP                                IPv4 scopes, reservations, leases,
                                      scope options and client tests

  Access control                      Shared folders, NTFS/share
                                      permissions and organizational
                                      units

  Group Policy                        Restricting system tools, software
                                      installation, updates and network
                                      changes

  User environments                   Roaming profiles and related access
                                      controls

  File Server Resource Manager        Quotas and file screening

  Remote administration               Remote Desktop, remote management
                                      and additional server onboarding

  Resilience                          Additional domain controller,
                                      AD/DNS replication and
                                      failover-related exercises

  VPN                                 Remote-access configuration and
                                      Windows 11 client testing
  -----------------------------------------------------------------------

## Selected technical commands

``` powershell
Get-NetAdapter
Get-NetIPConfiguration
Get-DnsClientCache
ipconfig /all
ipconfig /flushdns
ping <host>
tracert <host>
```

These are illustrative administration commands. The complete report
contains additional procedures, configuration steps and screenshots.

## Documentation

**[Read the complete technical
report](Windows_Server_2025_Pedro_Goncalves_Imagens_Alinhadas.docx)**

For best accessibility on GitHub, a PDF export can also be added to this
repository once it has been reviewed and optimized for file size.

## Security and publication notes

All examples should be used only in authorized lab environments. Before
publishing technical screenshots, verify that they do not disclose real
passwords, personal data, private network information, or identifying
details of third parties.

## Skills demonstrated

`Windows Server 2025` · `Active Directory` · `DNS` · `DHCP` · `GPO` ·
`PowerShell` · `VirtualBox` · `File Server` · `Storage` ·
`Network Troubleshooting` · `Remote Administration` · `VPN`

## Author

**Pedro Gonçalves** --- IT, Networking & Cybersecurity Portfolio

[GitHub profile](https://github.com/PedroGoncalves28286)
