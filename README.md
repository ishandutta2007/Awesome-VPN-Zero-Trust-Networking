# Awesome-VPN-Zero-Trust-Networking

## Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-VPN-Zero-Trust-Networking

# Top VPN & Zero Trust Networking Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on WireGuard Mesh, Zero Trust Network Access, Overlay Networking & Secure Remote Connectivity*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **VPN & Zero Trust Networking**. These systems connect users and devices through encrypted overlays—classic VPNs, WireGuard meshes, and Zero Trust Network Access (ZTNA)—without exposing every service to the public internet.

**Examples** include ZeroTier, Tailscale Enterprise, NetBird Cloud, Nebula Cloud, Cisco AnyConnect, WireGuard Business offerings, Perimeter 81, Twingate, NordLayer, Cloudflare Access, and **NetBird** (`netbirdio/netbird`)—connect devices into a secure private WireGuard mesh network.

**Open-source emphasis**: Overlay and WireGuard-based networking is rich in open source. **NetBird**, **Headscale**, **WireGuard**, **Nebula**, **OpenZiti**, and **Firezone** enable self-hosted zero-trust style connectivity. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Tailscale, NetBird Cloud, ZeroTier](https://tailscale.com/)**  
  Managed WireGuard/mesh overlay platforms—easy device enrollment, ACLs, and cross-cloud private networking.

- **[Cloudflare Access / Zero Trust, Twingate, Perimeter 81, NordLayer](https://www.cloudflare.com/zero-trust/)**  
  Zero Trust Network Access (ZTNA) products—identity-aware access to apps without full-network VPN.

- **[Cisco AnyConnect / Secure Client, other enterprise VPNs](https://www.cisco.com/)**  
  Traditional and hybrid enterprise remote-access VPN clients and concentrators.

- **[Other commercial mesh & ZTNA platforms](https://www.twingate.com/)**  
  Additional business VPN and zero-trust connectivity services.

## Open-Source GitHub Projects

### WireGuard Mesh & Tailscale-Compatible

- **[NetBird](https://github.com/netbirdio/netbird)**  
  Open-source WireGuard mesh platform—self-hostable control plane, SSO, and secure private networking for devices and servers.

- **[Headscale](https://github.com/juanfont/headscale)**  
  Open-source self-hosted implementation of the Tailscale control server—use official Tailscale clients with your own coordination layer.

- **[WireGuard](https://github.com/WireGuard/wireguard-tools)**  
  Foundational open VPN protocol and tools—fast, modern cryptography; building block for most mesh products above.

- **[Firezone](https://github.com/firezone/firezone)**  
  Open-source Zero Trust access platform based on WireGuard—self-hosted secure remote access with identity providers.

### Overlay & Zero Trust Frameworks

- **[Nebula](https://github.com/slackhq/nebula)**  
  Open scalable overlay networking from Slack—certificate-based trust, peer-to-peer tunnels, and host firewall integration.

- **[OpenZiti](https://github.com/openziti/ziti)**  
  Open Zero Trust networking platform—application-embedded or gateway-based connectivity with strong identity and posture concepts.

- **[ZeroTier (core components / community)](https://github.com/zerotier/ZeroTierOne)**  
  Open networking layer for virtual networks; commercial control plane available as SaaS.

- **[innernet](https://github.com/tonarino/innernet)**  
  Open private network system based on WireGuard with a focus on simple, audited design.

- **[Wesher](https://github.com/costela/wesher)**  
  Open simple WireGuard mesh with automatic cluster membership (e.g. for Docker/Swarm nodes).

### Classic Open VPN & Access

- **[OpenVPN](https://github.com/OpenVPN/openvpn)**  
  Long-standing open VPN solution—flexible TLS-based tunnels for site-to-site and remote access.

- **[softether / other community VPN servers](https://github.com/SoftEtherVPN/SoftEtherVPN)**  
  Multi-protocol open VPN server options for mixed client environments.

- **[Pritunl](https://github.com/pritunl/pritunl)**  
  Open distributed enterprise VPN server built on OpenVPN and WireGuard options.

### Additional Strong Open-Source Options

- **Self-hosted Tailscale-style mesh**: Headscale + Tailscale clients, or full NetBird.
- **App-level zero trust**: OpenZiti.
- **Cert-based overlay**: Nebula.
- **Simple WG mesh**: Wesher / innernet.
- **Composable stacks**: WireGuard → coordination (Headscale/NetBird) → IdP (Keycloak) → optional ZTNA gateway (Firezone).
- Commercial platforms still lead for managed global relays, support SLAs, and polished device UX at scale.

**Frameworks for building custom systems**:  
**NetBird** or **Headscale** for WireGuard mesh; **Firezone** for ZTNA-style access; **Nebula** or **OpenZiti** for alternative trust models; **WireGuard** alone for simple point-to-point links.  
Fully open private networking is production-ready for teams willing to operate a control plane.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- VPN and zero-trust systems protect sensitive paths—secure the control plane, rotate keys/certs, enforce SSO/MFA, and monitor peer enrollment. A compromised coordinator can affect the whole mesh.
- Open-source overlays offer data-path transparency and self-hosting. Commercial ZTNA/VPN shifts relay infrastructure and support to the vendor. Neither replaces endpoint security and least-privilege application design.

---

**Made for platform, security, and IT teams connecting users and services safely.**  
Let's expand open WireGuard mesh and zero-trust networking while recognizing the managed convenience that commercial Tailscale-class and ZTNA platforms deliver.
