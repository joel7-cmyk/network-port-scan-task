# Network Port Scan Task

## Objective
To scan a system and identify open ports.

## Tool Used
Nmap

## Target
192.168.3.116

## Open Ports Found
- 135 (MSRPC)
- 139 (NetBIOS)
- 445 (SMB)
- 5357 (WSDAPI)

## Risks
- SMB (445) can be vulnerable
- NetBIOS is outdated
- Open ports increase attack surface

## Conclusion
The system appears to be a Windows machine with file sharing enabled.
