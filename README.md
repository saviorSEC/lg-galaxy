# LG GALAXY — webOS TV data plane, ACR, ad-tech: where the data goes

Interactive map of the LG smart-TV data ecosystem: what a webOS TV
collects, the LG cloud estates it reports into, the ACR/ad partners in
the chain, and the last stop before the data is sold.

- Zones: 8 · Services: 29 · Links: 38
- Data: `data.json` (`{zones, services, links}`) — every node carries
  the endpoints, DNS, ASN and disclosure text collected for it
- Render: open `index.html` in any browser (no dependencies, no
  network calls)
- Live: https://saviorsec.github.io/lg-galaxy/

## The short answer

TV -> LG cloud (SDP + lgtvcommon.com data plane) -> ACR (Gracenote +
Alphonso) -> LG Ad Solutions -> advertisers / business partners -> the
data-broker ecosystem. LG's own CCPA disclosure lists the categories it
sells or shares and the recipient classes; LG Ad Solutions markets 363M+
"addressable secondary devices" built from TV-side network discovery of
non-LG devices.

## Boundary

Passive OSINT / public artifacts only: cert-transparency logs, DNS,
RDAP/registrations, LG and partner privacy policies, and public
reporting (Gamers Nexus / Level1Techs investigation 2026-09-07, press
2026-09-07..09). No active probing of LG or partner infrastructure, no
auth, no exploitation. Full research archive (with sources and
evidence files): github.com/saviorSEC/LG (private).
