---
title : "Verification"
weight : 7
pre : " <b> 7. </b> "
---

## Verification

- **EC2:** All SAP-related instances are running and reachable (via SSM/Session Manager or your chosen access).  
- **Network:** VPC routes via NAT work; endpoints (S3, SSM, EC2Messages, SSMMessages) are available.  
- **SAP:** Validate basic connectivity and services start-up as per your pattern.  
- **Logs:** Check CloudWatch/Application logs for errors.
