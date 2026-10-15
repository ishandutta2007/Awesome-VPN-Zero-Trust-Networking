# Awesome-VPN-Zero-Trust-Networking

## Top VPN & Zero Trust Networking Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on WireGuard Mesh, Zero Trust Network Access, Overlay Networking & Secure Remote Connectivity*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **VPN & Zero Trust Networking**. These systems connect users and devices through encrypted overlays—classic VPNs, WireGuard meshes, and Zero Trust Network Access (ZTNA)—without exposing every service to the public internet.

**Examples** include ZeroTier, Tailscale Enterprise, NetBird Cloud, Nebula Cloud, Cisco AnyConnect, WireGuard Business offerings, Perimeter 81, Twingate, NordLayer, Cloudflare Access, and **NetBird** (`netbirdio/netbird`)—connect devices into a secure private WireGuard mesh network.

**Open-source emphasis**: Overlay and WireGuard-based networking is rich in open source. **NetBird**, **Headscale**, **WireGuard**, **Nebula**, **OpenZiti**, and **Firezone** enable self-hosted zero-trust style connectivity. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
  - [WireGuard Mesh & Tailscale-Compatible](#wireguard-mesh--tailscale-compatible)
  - [Overlay & Zero Trust Frameworks](#overlay--zero-trust-frameworks)
  - [Classic Open VPN & Access](#classic-open-vpn--access)
  - [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## SaaS/Hosted Platforms

| 🏢 Platform / Service | 📝 Description & Primary Focus | 💰 Starting Tier Pricing | 🎁 Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- |
| **[Tailscale](https://tailscale.com/)** | Mesh VPN built on WireGuard providing identity-aware overlay networking, MagicDNS, access control lists (ACLs), and single sign-on (SSO) integration. | **$8.00 / user / month** (*Standard plan; $6.00/user/mo billed annually; unlimited users & devices*) | **Free forever Personal plan**: Up to 6 users, unlimited devices, 3 ACL groups, 50 tagged resources, and 1,000 ephemeral resource minutes/month. |
| **[NetBird Cloud](https://netbird.io/)** | Open-core Zero Trust WireGuard overlay networking platform with IdP SSO integration (Google, Okta, Microsoft Entra ID), routing peers, and centralized access controls. | **€6.00 (~$6.50) / user / month** (*Team plan; $5.00/user/mo billed annually; unlimited admins/users, MFA & event streaming*) | **Free forever plan**: Up to 5 users, up to 100 machines/devices, access controls, network routes, private DNS, and SSO integration (no credit card required). |
| **[Cloudflare Zero Trust](https://www.cloudflare.com/zero-trust/)** | Zero Trust Network Access (ZTNA) and Secure Web Gateway routing application traffic through Cloudflare’s global Anycast edge network with device client (WARP). | **$7.00 / user / month** (*Pay-as-you-go Standard tier; includes 30-day log retention and unlimited users*) | **Free forever plan**: Up to 50 users with full Access ZTNA, Gateway DNS/HTTP inspection, WARP client, 24-hour log retention, and community support. |
| **[Twingate](https://www.twingate.com/)** | Software-defined perimeter and ZTNA platform replacing legacy VPNs with least-privilege resource access, split tunneling, and zero network modifications. | **$5.00 / user / month** (*Teams plan, billed annually; $6.00/user/mo billed monthly; up to 100 users, Google Workspace SSO*) | **Free forever Starter plan**: Up to 5 users, up to 50 resources, 1 remote network, split tunneling, and community support (plus 14-day free trial of Business tier). |
| **[ZeroTier](https://www.zerotier.com/)** | Global software-defined overlay network connecting devices, cloud instances, and containers with layer-2/layer-3 virtual Ethernet mesh capabilities. | **$18.00 / month** (*Essential plan; includes 10 devices, 10 networks, and 5 admins; additional devices $2.00/device/month*) | **Free forever Basic plan**: Up to 10 connected devices/nodes, 1 network, 1 network administrator, and community support. |
| **[Firezone Cloud](https://www.firezone.dev/)** | Fast, WireGuard-based zero trust network access (ZTNA) platform with granular resource-level policies, multi-site routing, and native SSO identity synchronization. | **$5.00 / user / month** (*$50.00/seat/year billed annually, Team plan; up to 500 users, conditional access*) | **Free forever Starter plan**: Up to 6 users, 10 service accounts, 3 sites, resource-level policies, audit logs, and community support (plus 14-day free trial of Team plan). |
| **[GoodAccess](https://www.goodaccess.com/)** | Cloud VPN with zero-trust network access, dedicated private gateway with static IP, identity management, and DNS threat filtering for distributed teams. | **$7.00 / user / month** (*Essential plan, billed annually; $9.00/user/mo billed monthly; 5-user minimum commit*) | No permanent free tier; **14-day free trial** with full access to all premium features, dedicated gateway, and up to 100 users (no credit card required). |
| **[Perimeter 81](https://www.perimeter81.com/)** *(Check Point Harmony SASE)* | Cloud-delivered Secure Access Service Edge (SASE) and ZTNA platform offering identity-driven remote access, dedicated private gateways, and device posture checks. | **$8.00 / user / month** (*Essentials plan, billed annually; $10.00/user/mo billed monthly; 10-user minimum commit*) + $40.00/mo per dedicated gateway | No permanent free tier; **30-day money-back guarantee** across all plans + sales-guided evaluation Proof of Concept (PoC) for up to 50 users. |
| **[NordLayer](https://nordlayer.com/)** | Adaptive business VPN and remote access security platform built on the NordLynx (WireGuard) protocol with dedicated server IPs, threat protection, and network segmentation. | **$8.00 / user / month** (*Lite plan, billed annually; $10.00/user/mo billed monthly; 5-user minimum commit*) | No permanent free tier; **14-day money-back guarantee** on paid subscriptions (or 14-day sales-assisted business trial for qualifying teams). |
| **[OpenVPN CloudConnexa](https://openvpn.net/cloud-vpn/)** | Cloud-delivered virtual overlay network providing application-based routing, secure remote access, and zero-trust domain access across global Points of Presence. | **$7.00 / seat / month** (*Essential plan, billed annually; $8.50/seat/mo billed monthly; includes 24/7 support & SAML SSO*) | **Free forever Starter plan**: Up to 3 free concurrent connections/seats, 10 application domain routes, 10 IP services, and 7-day access visibility logs. |
| **[Defined Networking](https://www.defined.net/)** *(Managed Nebula)* | Managed cloud control plane for the open-source Nebula overlay mesh, providing an administrative web UI, automated PKI/key distribution, and host firewall rules. | **$1.00 / host / month** (*Pro plan; unlimited hosts, up to 100 external routes, automated failover, and priority support*) | **Free forever plan**: Up to 100 hosts, 2 external routes, and free managed lighthouse and default relay. |
| **[Cisco Secure Client](https://www.cisco.com/)** *(AnyConnect / Secure Access)* | Enterprise remote-access VPN client and Security Service Edge (SSE) platform offering endpoint posture assessment, MFA integration, and converged ZTNA/VPN tunnels. | **$6.00 to $6.50 / user / year** (~$0.50 - $0.54/user/month, *Secure Client Advantage / AnyConnect Plus, 25-user minimum commit SKU L-AC-PLS-1Y-S1*) | No permanent free tier; **14 to 30-day evaluation trial** available for up to 100 seats via Cisco sales representatives and certified partners. |
| **[Zscaler Private Access](https://www.zscaler.com/products/zscaler-private-access)** *(ZPA)* | Cloud-native zero trust network access (ZTNA) platform replacing legacy corporate VPNs by directly connecting authorized users to private applications without network exposure. | **~$11.67 / user / month** (*~$140.00 - $200.00/user/year baseline for ZPA Business Edition; 50-user minimum contract*) | No permanent free tier; **7-day hosted interactive test drive** and guided Proof of Concept (PoC) evaluation available upon request. |
| **[NetFoundry](https://netfoundry.io/)** *(OpenZiti Cloud)* | Fully managed zero trust networking-as-a-service platform built on OpenZiti, embedding microsegmentation and high-performance overlays into apps and cloud edges. | **~$29.00 / month** (*entry-level Teams tier for up to 20 endpoints; or customized volume quote on AWS Marketplace*) | **Free forever Teams plan**: Up to 10 endpoints / edge routers, global fabric connectivity, and web management console (no credit card required). |

---

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
