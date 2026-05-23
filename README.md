# atlas-air-worldwide-holdings

API Evangelist profile of **Atlas Air Worldwide Holdings**, the Purchase, New York-based global airfreight, charter, and aircraft leasing group that operates Atlas Air, Polar Air Cargo, and Titan Aviation Leasing. Fortune F1000 (rank 833 prior to going private).

## Profile

| Field | Value |
|---|---|
| Type | Company (private) |
| Headquarters | Purchase, New York, USA |
| Founded | 1992 (Michael Chowdry) |
| CEO | Michael Steen |
| Employees | 4,500+ |
| Footprint | 80+ countries, 330+ airports served |
| Fleet | 109+ aircraft — Boeing 747-8F, 747-400F, 747-400LCF Dreamlifter, 777F, 767-300BCF, 737-800BCF |
| Former ticker | Nasdaq: AAWW (delisted March 2023) |
| Owners | Apollo Global Management, J.F. Lehman & Company, Hill City Capital (take-private closed March 2023, ~US$5.2B all-cash) |

## Operating Companies

- **Atlas Air** — ACMI (Aircraft, Crew, Maintenance, Insurance), CMI (Crew, Maintenance, Insurance), commercial and military/government charter, passenger charter (VIP and high-capacity).
- **Polar Air Cargo** — scheduled airport-to-airport cargo network ("time-definite, airport-to-airport scheduled air cargo service"); historic 49% stake by DHL.
- **Titan Aviation Leasing** — commercial aircraft acquisition, leasing, and sale-leaseback portfolio.

## Notable Customers

- **Amazon Air** — Atlas operates Boeing 737-800BCF (and historically 767F and 747-8F) lift in the Prime Air middle-mile network.
- **DHL Express** — long-running ACMI relationship across 767-300F and 777F.
- **Boeing** — exclusive operator of the four-strong Boeing 747-400LCF Dreamlifter fleet supporting 787 production.
- **U.S. Department of Defense / Air Mobility Command** — Civil Reserve Air Fleet (CRAF) participant.

## Why no APIs?

Atlas Air Worldwide is a freight and aircraft-leasing carrier, not a software company. There is no public developer portal, no published OpenAPI specs, no SDKs, and no public rate-limit/pricing surface. Customer integrations are handled through private partner channels — EDI, Cargo-IMP/XML messaging, freight-forwarder portals, and account-managed connectivity. The only self-service web surfaces are:

- Polar Air Cargo airwaybill (AWB) shipment tracking on polaraircargo.com
- The Special Loads request form at `specialloads.atlasair.com`
- The "Tailwinds" corporate blog and the Atlas Air Worldwide press release archive

A GitHub organization `Atlas-Air-Data-Platform` was registered in April 2025 with no public repositories at the time of profiling.

## Data captured in `apis.yml`

- Three operating company / portal URLs (Atlas Air, Polar Air Cargo, Atlas Air Worldwide holdings site)
- Console links for shipment tracking and Special Loads requests
- Blog and press-release URLs (corporate ChangeLog surrogate)
- Sales / headquarters contact details
- Regional office locations across the Americas, EMEIA, and Asia-Pacific
- Notable customer roster (Amazon Air, DHL, Boeing, DoD/AMC)
- LinkedIn and GitHub presence
- Ownership / take-private partnership history

## Sources

- [www.atlasairworldwide.com](https://www.atlasairworldwide.com)
- [www.atlasair.com](https://www.atlasair.com)
- [www.polaraircargo.com](https://www.polaraircargo.com)
- [Atlas Air Worldwide press releases](https://www.atlasairworldwide.com/newsroom/press-releases/)
- [Tailwinds blog](https://www.atlasairworldwide.com/tailwinds-atlas-air-worldwide-blog/)
- Wikipedia — Atlas Air Worldwide Holdings
