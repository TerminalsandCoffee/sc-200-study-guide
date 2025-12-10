# Detection Rules

Microsoft Sentinel analytics rules, scheduled queries, and detection logic.

## Structure

- `scheduled-rules/` - Scheduled analytics rules (1-14 day intervals)
- `nrt-rules/` - Near Real-Time (NRT) rules (1 minute intervals)
- `fusion-rules/` - Fusion and ML-based detection rules
- `custom-rules/` - Custom detection scenarios
- `templates/` - Rule templates and starting points

## Rule Components

Each rule should include:
- KQL query
- Rule configuration (severity, tactics, techniques)
- Entity mapping
- Alert details and descriptions
- Testing notes and validation

## Exam Focus Areas

- Creating scheduled analytics rules
- Configuring NRT rules
- Using Fusion rules for multi-signal correlation
- Custom entity mapping
- Alert grouping and suppression
- Rule tuning and optimization

