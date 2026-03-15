# SOC Analyst Home Lab

## Project Overview

This project demonstrates the creation of a **Security Operations Center (SOC) home lab** used to simulate cyber attacks and detect suspicious activity using a SIEM platform.

The lab replicates a simplified enterprise security environment where endpoint activity is monitored and investigated.

## Lab Architecture

Ubuntu Attacker → Windows Endpoint → Sysmon Logging → Splunk SIEM

## Tools Used

* VirtualBox
* Windows 10
* Ubuntu
* Sysmon
* Splunk

## Skills Demonstrated

Security monitoring
SIEM log analysis
Threat detection
Incident investigation
Endpoint logging
Security documentation

## Attack Simulation

A simulated attacker executed commands on the Windows system including:

* account creation
* process execution
* system enumeration

These actions generated logs which were analyzed in Splunk.

## Detection Example

Splunk query used to detect process creation:

index=main EventCode=4688

This query identifies processes executed on the monitored endpoint.

## Investigation Outcome

The SIEM detected suspicious activity including:

* creation of a new user account
* unusual command execution
* process activity linked to enumeration

An incident report was created documenting the investigation.

## Screenshots

See the **screenshots folder** for evidence of the lab setup and detections.

## Author

Cybersecurity student building practical SOC analyst skills through hands-on labs.
