# Free Compute — verified daily section (2026-11-17)

| Provider | Offer | What's free | Card? | Auto-charge? | Quota / expiry |
|---|---|---|---|---|---|
| AWS Free Tier | AWS Free Tier new account credits | Up to $200 in credits for new customers ($100 immediately, up to $100 more by exploring key services) | None | False | up to $200 · expires 6 months |
| AWS Free Tier | AWS Free plan service access | Free usage of select services across over 90 services for up to 6 months | None | False | over 90 services · expires 6 months |
| AWS Free Tier | Short-term free trials | Limited free trials of selected Paid plan services, with eligible credits applying to usage beyond trial limits | None | None | — |
| AWS Free Tier | Always-free services | 30+ AWS services always free within monthly usage limits on both the Free and Paid plans | None | None | 30+ AWS services |
| Azure Free Account | Azure free account | Free monthly amounts of 20+ popular services for 12 months and 65+ always-free services, plus $200 credit to use within 30 days | True | False | $200 credit; 20+ services free for 12 months; 65+ always-free services · expires 30 days for credit; 12 months for popular services |
| Azure Free Account | Azure Virtual Machines (Linux or Windows) | 750 hours each of B1s, B2pts v2 (Arm-based), and B2ats v2 (AMD-based) burstable VMs | None | None | 750 hours each of B1s, B2pts v2, and B2ats v2 burstable VMs · expires 12 months |
| Azure Free Account | Azure Database for PostgreSQL Flexible Server | 750 hours of Flexible Server—Burstable B1MS Instance, 32 GB storage, and 32 GB backup storage | None | None | 750 hours Burstable B1MS, 32 GB storage, 32 GB backup storage · expires 12 months |
| Azure Free Account | Azure Container Registry | 1 Standard tier registry with 100 GB storage and 10 webhooks | None | None | 1 Standard tier registry with 100 GB storage and 10 webhooks · expires 12 months |
| Azure Free Account | Azure Cosmos DB | 1,000 request units per-second provisioned throughput with 25 GB storage | None | None | 1,000 request units per-second provisioned throughput with 25 GB storage |
| Azure Free Account | Azure Virtual Machines (Linux/Windows) | 750 hours each of B1s, B2pts v2 (Arm-based), and B2ats v2 (AMD-based) burstable VMs | None | None | 750 hours each of B1s, B2pts v2ub, and B2ats v2ub burstable VMs · expires 12 months |
| Azure Free Account | Azure Database for PostgreSQL | 750 hours of Flexible Server—Burstable B1MS Instance, 32 GB storage, and 32 GB backup storage | None | None | 750 hours of Flexible Server—Burstable B1MS Instance, 32 GB storage, and 32 GB backup storage · expires 12 months |
| Azure Free Account | Azure SQL Database (serverless) | 100,000 vCore seconds of SQL database serverless usage per month with 32 GB of storage | None | None | 100,000 vCore seconds per month with 32 GB of storage |
| Azure Free Account | Azure Functions | 1 million requests | None | None | 1 million requests |
| Cohere (trial key) | Trial API key | A Trial API key automatically created with each account for API access | None | None | — |
| Google Cloud Free Tier | $300 free credit for new customers | $300 in free credit to try Google Cloud products | None | None | $300 |
| Google Cloud Free Tier | Compute Engine e2-micro instance | 1 e2-micro instance per month | None | None | 1 e2-micro instance per month |
| Google Cloud Free Tier | Cloud Storage Standard Storage | 5 GB-months Standard Storage | None | None | 5 GB-months Standard Storage |
| Google Cloud Free Tier | BigQuery queries | 1 TB queries per month | None | None | 1 TB queries per month |
| Google Cloud Free Tier | Cloud Run requests | 2 million requests per month | None | None | 2 million requests per month |
| Google Cloud Free Tier | Google Kubernetes Engine cluster | One Autopilot or Zonal cluster per month | None | None | One Autopilot or Zonal cluster per month |
| Modal (serverless GPU credits) | Starter plan monthly free credits | $30/month in free compute credits | None | None | $30 / month |
| Modal (serverless GPU credits) | Team plan monthly free credits | $100/month in free compute credits | None | None | $100 / month |
| Modal (serverless GPU credits) | Starter free network egress | 1 TiB per month of free network egress and 1 TiB/mo free volume storage on the Starter plan | None | None | 1 TiB / month · expires monthly |
| Modal (serverless GPU credits) | Team free network egress | 10 TiB per month of free network egress on the Team plan | None | None | 10 TiB / month · expires monthly |
| Modal (serverless GPU credits) | Enterprise free network egress | 100 TiB per month of free network egress | None | None | 100 TiB / month · expires monthly |
| Modal (serverless GPU credits) | Free volume storage | 1 TiB per month of included volume storage | None | None | 1 TiB / mo · expires monthly |
| Modal (serverless GPU credits) | Startup credit grants | Free compute credits for early-stage startups on Modal | None | None | — |
| Modal (serverless GPU credits) | Academic credit grants | Up to $10k free compute credits for graduate students, labs, and researchers | None | None | $10k |
| Modal (serverless GPU credits) | Free network egress (Starter) | 1 TiB/month free network egress | None | None | 1 TiB / month |
| Modal (serverless GPU credits) | Free network egress (Team) | 10 TiB/month free network egress | None | None | 10 TiB / month |
| Modal (serverless GPU credits) | Free network egress (Enterprise) | 100 TiB/month free network egress | None | None | 100 TiB / month |
| Modal (serverless GPU credits) | Volumes free storage | 1 TiB/month free volume storage | None | None | 1 TiB / mo |
| Oracle Cloud (OCI) Always Free | Oracle Cloud Free Trial credit | US$300 of free cloud credit to use on all eligible Oracle Cloud Infrastructure services | True | None | US$300 · expires up to 30 days |
| Oracle Cloud (OCI) Always Free | Always Free services | Always Free services are available for an unlimited period of time at no cost | None | None | — |
| Oracle Cloud (OCI) Always Free | Always Free AMD-based Compute | AMD-based Compute available as an Always Free service | None | None | — |
| Oracle Cloud (OCI) Always Free | Always Free Arm-based Ampere A1 Compute | Arm-based Ampere A1 Compute available as an Always Free service | None | None | — |
| Oracle Cloud (OCI) Always Free | Always Free Block Volume | Block Volume storage available as an Always Free service | None | None | — |
| Oracle Cloud (OCI) Always Free | Always Free Autonomous Data Warehouse | Autonomous Data Warehouse available as an Always Free service | None | None | — |

## Field-tested notes (ours, not marketing)

- Vultr prepaid-card field test (2026-11-13/14): prepaid at $0 fails -> account SUSPENSION (recoverable), not deletion; stopped instances keep billing (no pause); snapshots keep billing after destroy ($0.05/GB-mo compressed); pending charges post in batches, not per-hour.
- OCI Always Free is the only big-cloud tier this stack verified by actually USING it: 2x E2.1.Micro + 200GB boot volumes, zero charges, 100+ days.
- NVIDIA NIM free keys are per-account daily-token pools for prototyping — fine for a single developer, not a multi-tenant backend (see free-router lesson).
