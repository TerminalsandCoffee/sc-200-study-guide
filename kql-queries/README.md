# KQL Queries

Kusto Query Language (KQL) queries for detection, hunting, and analysis in Microsoft Sentinel and Microsoft 365 Defender.

## Structure

- `detection-rules.kql` - Analytics rules and scheduled queries for automated detection
- `hunting-queries.kql` - Proactive threat hunting queries
- `workbook-snippets.kql` - Query snippets for Sentinel workbooks
- `investigation-queries.kql` - Queries for incident investigation and analysis
- `baseline-queries.kql` - Baseline and data exploration queries

## Query Categories

### Detection Rules
- Scheduled analytics rules
- Near Real-Time (NRT) rules
- Fusion rules
- ML-based detections

### Threat Hunting
- Anomaly detection
- Behavioral analysis
- Threat intelligence matching
- Custom hunting scenarios

### Investigation
- Entity expansion queries
- Timeline reconstruction
- Correlation queries
- Data enrichment

## Best Practices

- Comment your queries with purpose and context
- Use parameterization where possible
- Include performance considerations
- Test queries before deploying as rules
- Document data sources and table schemas

