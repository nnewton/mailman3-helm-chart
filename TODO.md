## Mailman3 Helm Chart TODOs

- Add TLS support so REST API traffic uses HTTPS and mounts certificates automatically.
- Implement bounce processing, either natively or by integrating with Amazon SES/SNS workflows.
- Build lambda/S3 polling for SES inbound mail and hand off messages to Postfix for delivery.
