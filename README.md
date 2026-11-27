# Operation Silent Script

## Project Overview
A hands-on SOC analyst investigation focused on Windows endpoint monitoring, Sysmon event analysis, process lifecycle correlation, and digital forensic evidence preservation.

## Tools and Technologies
- Windows 11
- Oracle VirtualBox
- Microsoft Sysmon
- PowerShell
- Windows Event Viewer
- SHA256 hashing

## Investigation Results

| Event ID | Description | Count |
|---|---|---:|
| 1 | Process Creation | 2,112 |
| 5 | Process Termination | 1,529 |
| 4 | Service State Change | 8 |
| 16 | Configuration Change | 1 |
| | **Total** | **3,650** |

## Key Findings
- Identified a parent-child relationship between powershell.exe and conhost.exe.
- Correlated process creation and termination using matching Process GUIDs.
- Calculated a process lifetime of 24 minutes and 52.717 seconds.
- Verified evidence integrity using SHA256 hashes.
- No malicious activity was confirmed in the reviewed records.

## Skills Demonstrated
- Security event analysis
- Endpoint monitoring
- Threat investigation
- PowerShell log filtering
- Process lifecycle correlation
- Digital forensic evidence preservation
- SOC incident reporting

## Project Evidence
- OSS_Incident_Report_Public.txt
- OSS_Event_Statistics_Public.csv
- OSS_Process_Lifecycle_Public.csv

## Disclaimer
This project was conducted in a controlled laboratory environment for educational and professional development purposes. Published evidence is sanitized to protect sensitive information. Original forensic evidence is stored privately.
