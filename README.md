# Actual conf
Unique subnet with workstations

# Wants
Architecture with safe network.

Access to DVWA is protected and run as a docker.

DVWA can't be modified.

# Fears
External connection by attacker

Bad manipulation from the students

# Infrastructure Needs
- Internal infrastructure resolved by DNS underthe domain cyberdiploma.corp.

- Private CA (Certificate Authority) for delivering the certificates needed.

- They need proof that any instance deployed is following a basic hardening guide.

- Workstations authenticate against a central base of identity.

- Linux Workstations authenticated on a central location (i.e.: FreeIPA).

- (Bonus for the boldest - meaning it is not mandatory to provide this but it will provide
additional client satisfaction) They need an Active Directory for workstation
authentication (Windows).

# Application Needs

