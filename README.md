# AWS-NETWORKS-SECURITY
VPC Traffic flow and security
# AWS VPC Traffic Control & Security Project

![AWS VPC Architecture](https://d1.awsstatic.com/security-center/architecture_diagrams/aws-vpc-architecture.8b739b1f5fe8d8a5f5d5b5d5c5d5b5d5.png)

## 🌐 Project Overview
Designed a secure **Amazon Virtual Private Cloud (VPC)** network with:
- **Public/Private Subnets** with route tables
- **Security Groups** (resource-level firewall)
- **Network ACLs** (subnet-level traffic rules)
- **Internet Gateway** connectivity

**Key Achievement**: Implemented layered security resembling real-world infrastructure (Security Groups as "guards", ACLs as "traffic cops").

---

## 🔧 AWS Services Used
| Service | Purpose |
|---------|---------|
| Amazon VPC | Network isolation |
| Route Tables | Traffic routing (like GPS) |
| Security Groups | Resource-level security |
| Network ACLs | Subnet-level packet filtering |
| Internet Gateway | Public subnet connectivity |

---

## 🛠️ Core Implementations
### 1. Route Tables Configuration
```text
Destination: 0.0.0.0/0 (All internet traffic)  
Target: NextWorkIG (Internet Gateway)  
