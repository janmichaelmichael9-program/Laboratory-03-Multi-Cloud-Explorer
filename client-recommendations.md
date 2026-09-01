# Client Recommendations

---

## Client A — Startup Company
**Recommended Platform:** AWS

**Recommendation:** AWS is ideal for startups due to a generous Free Tier, pay-as-you-go pricing, and ability to scale instantly as the company grows. The massive community and documentation reduce learning time.

**Services to use:**
1. **Amazon EC2** — Host the mobile app backend
2. **Amazon S3** — Store app assets and user data
3. **Amazon RDS** — Manage app database

---

## Client B — University
**Recommended Platform:** Microsoft Azure

**Recommendation:** Since the university already uses Windows Server, Microsoft 365, and Active Directory, Azure integrates with zero major changes. Single sign-on and existing licenses reduce cost and complexity.

**Services to use:**
1. **Azure Virtual Machines** — Migrate Windows Server workloads
2. **Entra ID** — Reuse existing user identities
3. **Azure SQL Database** — Migrate university databases

---

## Client C — AI Research Company
**Recommended Platform:** Google Cloud Platform (GCP)

**Recommendation:** GCP leads in AI/ML tooling and provides world-class GPU/TPU hardware. Vertex AI and BigQuery offer an end-to-end research environment with Kubernetes for scaling experiments.

**Services to use:**
1. **Vertex AI** — Build, train, and deploy ML models
2. **Google Compute Engine** — High-performance VMs with GPUs
3. **Google BigQuery** — Store and analyze large datasets

---

## Client D — Global E-Commerce Company
**Recommended Platform:** AWS

**Recommendation:** AWS has the most mature global infrastructure and auto-scaling tools. Its proven reliability and auto-scaling handle traffic spikes from shoppers worldwide.

**Services to use:**
1. **Amazon EC2 with Auto Scaling** — Handle variable web traffic
2. **Amazon S3 + CloudFront** — Fast global delivery of storefront
3. **Amazon RDS (Multi-AZ)** — Highly available database

---

## Multi-Cloud Decision Matrix (Checkpoint 6)

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | Free Tier, low entry cost, massive community, easy scaling |
| Enterprise Organization | Azure | Best hybrid support, compliance, familiar management tools |
| Microsoft Environment | Azure | Native AD, 365, Windows, and .NET integration |
| AI / Machine Learning | GCP | Vertex AI, TPUs, BigQuery, and ML APIs |
| Kubernetes Deployment | GCP | GKE is built on original Kubernetes; most mature & standard |
| Global Web Application | AWS | Most regions, edge locations, mature auto-scaling |
