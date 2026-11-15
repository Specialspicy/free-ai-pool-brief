# Free Compute — verified daily section (2026-11-15)

| Provider | Offer | What's free | Card? | Auto-charge? | Quota / expiry |
|---|---|---|---|---|---|
| Cohere (trial key) | Trial API key | Trial API key automatically created when an account is created, available to copy from dashboard | None | None | — |
| Google Cloud Free Tier | $300 free credit for new customers | $300 in free credit to try Google Cloud products and build a proof of concept | None | None | $300 |
| Google Cloud Free Tier | Compute Engine e2-micro instance | 1 e2-micro instance per month | None | None | 1 e2-micro instance per month |
| Google Cloud Free Tier | Cloud Storage Standard Storage | 5 GB-months Standard Storage | None | None | 5 GB-months Standard Storage |
| Google Cloud Free Tier | BigQuery queries | 1 TB queries per month | None | None | 1 TB queries per month |
| Google Cloud Free Tier | Cloud Run requests | 2 million requests per month | None | None | 2 million requests per month |
| Google Cloud Free Tier | Google Kubernetes Engine cluster | One Autopilot or Zonal cluster per month | None | None | One Autopilot or Zonal cluster per month |
| Modal (serverless GPU credits) | Starter plan monthly free credits | $30 per month in free compute credits | None | None | $30 / month · expires monthly |
| Modal (serverless GPU credits) | Team plan monthly free credits | $100 per month in free compute credits | None | None | $100 / month · expires monthly |
| Modal (serverless GPU credits) | Starter free network egress | 1 TiB per month of free network egress | None | None | 1 TiB / month · expires monthly |
| Modal (serverless GPU credits) | Team free network egress | 10 TiB per month of free network egress | None | None | 10 TiB / month · expires monthly |
| Modal (serverless GPU credits) | Enterprise free network egress | 100 TiB per month of free network egress | None | None | 100 TiB / month · expires monthly |
| Modal (serverless GPU credits) | Free volume storage | 1 TiB per month of included volume storage | None | None | 1 TiB / mo · expires monthly |
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
