# Logic App Playbooks

Automated response playbooks using Azure Logic Apps for Microsoft Sentinel incidents.

## Structure

- `incident-response/` - Playbooks for incident triage and response
- `enrichment/` - Playbooks for data enrichment (Threat Intelligence, etc.)
- `notification/` - Playbooks for alerting and notifications
- `remediation/` - Playbooks for automated remediation actions
- `templates/` - Reusable playbook templates

## Playbook Categories

### Incident Response
- Incident creation and assignment
- Entity enrichment
- Automated investigation workflows
- Response coordination

### Enrichment
- Threat intelligence lookups
- User context gathering
- Device information retrieval
- IP/domain reputation checks

### Notification
- Email notifications
- Teams/Slack integration
- PagerDuty/Splunk On-Call
- Custom webhook notifications

### Remediation
- Account disablement
- IP blocking
- Service isolation
- Automated ticket creation

## Exam Focus

- Creating Logic App playbooks
- Triggering playbooks from analytics rules
- Using Sentinel connectors
- Playbook permissions and managed identities
- Testing and troubleshooting playbooks

