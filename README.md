# Splunk SOC Lab

## Project Overview

This project demonstrates a hands-on Security Operations Center (SOC) Tier 1 investigation using Splunk Enterprise. It focuses on monitoring Windows Security events and Linux authentication logs, identifying security-relevant activity, and presenting findings in a Splunk dashboard.

## Tools and Technologies

- Splunk Enterprise
- Splunk Universal Forwarder
- Windows Security Event Logs
- Kali Linux
- SPL (Search Processing Language)

## Lab Environment

- **Windows:** Splunk Enterprise and Windows Security event monitoring
- **Linux:** Kali Linux forwarding authentication logs to Splunk
- **Data Sources:** Windows Security logs and Linux `/var/log/auth.log`

## Investigations

- Failed Windows logons (Event ID 4625)
- Successful Windows logons (Event ID 4624)
- Windows account creation (Event ID 4720)
- Local security group changes (Event ID 4732)
- Windows process creation events (Event ID 4688)
- Linux authentication failures
- Linux sudo activity
- Linux root session activity

## Dashboard

The Splunk dashboard provides an overview of collected Windows and Linux events and selected authentication and account-management activity.

See the [`screenshots`](screenshots/) folder for dashboard and investigation evidence.

## Key Learning Outcomes

- Collect and search Windows and Linux security logs in Splunk
- Investigate authentication and account-management events
- Review privileged group changes
- Build a security monitoring dashboard
- Document findings for a SOC portfolio

## Notes

This is a personal lab project using controlled test activity. Events shown in the dashboard are not automatically malicious; findings require investigation and context.

## Author

Adnan Ahmed