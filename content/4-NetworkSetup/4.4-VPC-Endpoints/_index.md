---
title : "VPC Endpoints"
weight : 4
pre : " <b> 4.4. </b> "
---

## VPC Endpoints (Images 30–41)

1) Open **Endpoints**.  
![30](/images/erp/30.png)

2) Click **Create endpoint** (you will create **4** endpoints).  
![31](/images/erp/31.png)

### Endpoint 1 — S3 (Gateway)
- Choose service ending with `.s3`.  
![32](/images/erp/32.png)
- Configure as shown.  
![33](/images/erp/33.png)
- **Create endpoint**.  
![34](/images/erp/34.png)

### Endpoint 2 — SSM (Interface)
- Service ending with `.ssm`.  
![35](/images/erp/35.png)
- Configure and create.  
![36](/images/erp/36.png)
![37](/images/erp/37.png)
- Check it appears.  
![38](/images/erp/38.png)

### Endpoint 3 — EC2Messages (Interface)
- Service ending with `.ec2messages`.  
![39](/images/erp/39.png)

### Endpoint 4 — SSMMessages (Interface)
- Service ending with `.ssmmessages`.  
![40](/images/erp/40.png)

### Verify
- Confirm all endpoints are listed.  
![41](/images/erp/41.png)
