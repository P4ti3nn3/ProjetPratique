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
- Web app for grades withe :
    - SSO
    - Redondant
    - Accessible from outside

# Application format   
- A Public page explaining the goal of the app

- A Landing Page when authenticated explaining the app context. They want to
integrate on this page a Motivational quote of the day changing every time to
motivate their users !

- An administration only page allowing to assign users a role
(student/teacher/administration). This page should also allow the admin user
to create a course

- A teacher only page allowing to add a grade to a student for an existing
course,

- A student only page allowing them to consult their grades,

- A web API needs to be created to allow them to automate their tasks.


