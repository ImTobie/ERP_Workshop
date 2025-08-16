---
title : "VPC Endpoints"
weight : 4
pre : " <b> 4.4. </b> "
---

## VPC Endpoints (Ảnh 30–41)

1) Mở **Endpoints**.  
![30](/images/erp/30.png)

2) Bấm **Create endpoint** (tạo **4** endpoints).  
![31](/images/erp/31.png)

### Endpoint 1 — S3 (Gateway)
- Chọn service `.s3`.  
![32](/images/erp/32.png)
- Cấu hình như hình.  
![33](/images/erp/33.png)
- Bấm **Create endpoint**.  
![34](/images/erp/34.png)

### Endpoint 2 — SSM (Interface)
- Service `.ssm`.  
![35](/images/erp/35.png)
- Cấu hình và tạo.  
![36](/images/erp/36.png)
![37](/images/erp/37.png)
- Kiểm tra hiển thị.  
![38](/images/erp/38.png)

### Endpoint 3 — EC2Messages (Interface)
- Service `.ec2messages`.  
![39](/images/erp/39.png)

### Endpoint 4 — SSMMessages (Interface)
- Service `.ssmmessages`.  
![40](/images/erp/40.png)

### Kiểm tra
- Xác nhận tất cả endpoints hoạt động.  
![41](/images/erp/41.png)
