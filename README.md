# Ldap
The Lightweight Directory Access Protocol (LDAP) is a vendor-neutral software protocol used to lookup information or devices within a network. Whether you want to build a
central authentication server for your organization or want to simplify access to internal servers and printers, LDAP is the answer.

## Overview

This repository contains NeoLoad Advanced Actions that allows performance testers using NeoLoad to connect LDAP Server & perform lookup for account.
 Other types of look also can implement.

| Property           | Value                                                                         |
|--------------------|-------------------------------------------------------------------------------|
| Maturity           | Experimental                                                                  |
| Support            | Supported by Neotys                                                           |
| Author             | Neotys                                                                        |
| License            | [BSD Simplified](https://www.neotys.com/documents/legal/bsd-neotys.txt)       |
| NeoLoad            | 6.5.1 (Enterprise or Professional Edition w/ Integration & Advanced Usage)    |
| Bundled in NeoLoad | Yes                                                                           |
| Download Binaries  | See the [latest release](https://github.com/Neotys-Labs/Ldap/releases/tag/ldap-0.0.1) |


## Installation

1. Download the [latest release](https://github.com/Neotys-Labs/Ldap/releases/tag/ldap-0.0.1)
1. Read the NeoLoad documentation to
   see [How to install a custom Advanced Action](https://www.neotys.com/documents/doc/neoload/latest/en/html/#25928.htm)

## Advanced Actions definitions
### ldapConnect

This Advanced Action establishes a connection to a LDAP Server.
Example:
<p align="center"><img src="/screenshots/connect.jpg" alt="Connect" /></p>

### ldaplookup

This Advanced Action perform lookup .
Example:
<p align="center"><img src="/screenshots/Lookup.jpg" alt="lookup" /></p>

## ChangeLog

* Version 0.0.1 (Apr 1st 2022): perform Account lookup

