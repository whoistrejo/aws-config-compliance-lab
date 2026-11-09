# Verification
```bash
aws configservice describe-configuration-recorder-status
aws configservice describe-config-rules
aws configservice get-compliance-details-by-config-rule --config-rule-name s3-bucket-public-read-prohibited
```
Initial evaluations may take time. AWS Config is billable based on configuration items and rule evaluations. This lab is single-account and single-region; an organization aggregator is a separate extension.
