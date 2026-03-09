# Production-Ready Three-Tier VPC Architecture

## **Project Objective:** Design and deploy a highly available, secure, and cost-optimized VPC architecture suitable for production e-commerce workloads.


![AWS](https://img.shields.io/badge/AWS-VPC%20Design-FF9900?style=flat-square&logo=amazonaws)
![Status](https://img.shields.io/badge/Status-%20Complete-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

## Project Overview
This project implements a highly available VPC design for a three-tier (Web/App/DB) application. I designed this as part of my AWS Solutions Architect Associate certification preparation to gain hands-on experience with network architecture.

**Key Objectives:**
- Design a scalable VPC supporting multiple Availability Zones
- Implement proper network segmentation for security
- Plan for future growth with reserved CIDR blocks
- Follow AWS best practices for high availability


## Architecture Diagram
![vpc design](screenshots/vpc_design.drawio.png)


---

## VPC Specifications

| Parameter | Value | Description |
|-----------|-------|-------------|
| **VPC CIDR** | `10.16.0.0/16` | 65,536 total IP addresses |
| **Region** | `us-east-1` | N. Virginia |
| **Availability Zones** | `3` | a, b, c |
| **Total Subnets** | `12` | 4 per AZ |
| **Subnet Mask** | `/20` | 4,096 IPs per subnet |

---


---


## References

- [AWS VPC Documentation](https://docs.aws.amazon.com/vpc/)
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- [VPC CIDR Calculator](https://www.davidc.net/sites/default/subnets/subnets.html)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---