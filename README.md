# VPNKit the ultimate OpenVPN in a container solution
## Why I started this project
S. Korean Government started DNS spoofing and SNI eavesdropping to censor
some copyright violators. However, this censorship clearly violates privacy
and could expand to political materials easily.

To solve this problem, It is important to remove huddle from OpenVPN such as,
clumsy certificate management `(easy-rsa does not quite cut it), frustrating
.conf files.

## What this project do?
This project automates two things from OpenVPN configuration: OpenVPN.conf and
CA management.

Docker startup script will automate OpenVPN configuration and companion project,
Project Ecthelion will provide easy-to-use, user friendly certificate management.

## Licensing
To ensure biggest freedom to its users, this project chooses Affero GPL v3 as
project's license.
