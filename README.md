Hi, I’m David 👋. I’m a software engineer focused on backend systems, data, and infrastructure. I enjoy building tools that solve practical problems and figuring out how to make them reliable and easy to operate.

## Work

**Sep 2022–present · AccuWeather for Business · Backend Software Engineer (Contractor)**

I build and maintain Go services that ingest weather warnings, evaluate customer-specific alert rules, and deliver notifications. I helped migrate public weather warnings to a new map interface, working across PostgreSQL/PostGIS configuration, backend APIs, and the customer portal. I also support production releases and investigate issues across the alert pipeline.

## Infrastructure & automation

I run a self-hosted platform on Proxmox. I use Terraform to provision virtual machines and containers, Ansible to configure hosts, and Docker Compose to deploy applications.

- **Deployments and CI.** I set up a self-hosted Forgejo instance and an isolated CI runner. I pin application versions and write runbooks for deployment and recovery.
- **Monitoring and recovery.** I built dashboards for network, storage, and host health, set up service checks with Uptime Kuma, and developed backup and restore workflows with Restic.

## Go and financial data

- **go-estado-cuenta-mx.** I built this library to extract account details and transactions from Mexican bank statement PDFs. It supports BBVA and HSBC layouts and provides diagnostics when parsing encounters issues. [Repository and quick start](https://github.com/DavidSerranoG/go-estado-cuenta-mx#inicio-rápido)
- **go-satcfdi.** I contributed the initial implementation of a Go client for Mexico’s SAT web services for bulk CFDI downloads and invoice status checks. [Repository](https://github.com/HerramientasSATGobMX/go-satcfdi)

## MLOps

- **Pricing MLOps.** I worked on the Azure infrastructure and model pipeline for a team project at Tecnológico de Monterrey. My contributions included event-driven orchestration, Azure ML pipeline components, versioned outputs, and run auditing. [Azure platform](https://github.com/tecmx-team46-pricing/pricing-mlops-platform) · [Model pipeline](https://github.com/tecmx-team46-pricing/pricing-mlops)
- **Model serving with MLflow.** I set up model serving with Docker and Caddy, documented the prediction API with OpenAPI, and wrote an AWS Lightsail deployment guide. [Serving PR](https://github.com/DannyAvilaL/MLOPs_30-/pull/9) · [Deployment guide PR](https://github.com/DannyAvilaL/MLOPs_30-/pull/2)

## Open source contributions

- **Material UI.** I reported and fixed an Autocomplete focus bug that kept users from moving to the next field with Enter. The fix was merged in 2019. [Issue](https://github.com/mui/material-ui/issues/18574) · [Merged PR](https://github.com/mui/material-ui/pull/18584)
