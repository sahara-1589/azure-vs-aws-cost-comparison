# AWS vs Azure Cost Comparison Report

## Introduction
This report compares AWS and Azure pricing for hosting a small web application using equivalent compute and storage resources.

---

## AWS Summary
- Compute: $7.59
- Storage: $1.15
- Data Transfer: $0.00
- Total: **$8.74/month**

---

## Azure Summary
- Compute: $9.50
- Storage: $1.00
- Data Transfer: $0.00
- Total: **$10.50/month**

---

## Cost Comparison Table

| Category        | AWS Cost | Azure Cost |
|----------------|----------|------------|
| Compute        | $7.59    | $9.50      |
| Storage        | $1.15    | $1.00      |
| Data Transfer  | $0.00    | $0.00      |
| **Total**      | **$8.74**| **$10.50** |

---

## Findings
AWS is more cost-effective for this small Linux-based workload due to lower compute pricing. Azure offers slightly cheaper storage but higher VM costs.

---

## Discount Mechanisms

### AWS
- Savings Plans
- Reserved Instances

### Azure
- Reserved VM Instances
- Azure Hybrid Benefit

---

## Cost Optimization Strategies
1. Use burstable instance types (t3.micro / B1s)
2. Use Reserved pricing for long-term workloads
