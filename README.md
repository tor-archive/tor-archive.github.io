# TOR Node Archive

tor-archive.github.io

The most comprehensive historical TOR node intelligence feed available. Every IP that has ever operated as a TOR relay is indexed with full activity timeline, node role, geolocation, and autonomous system attribution.

**212,000+ unique IPs** tracked since 2024 - updated automatically every 3 hours.

## Live Dashboard

**[index.html](index.html)** - open in any browser, zero dependencies, loads the JSON feed client-side.

### Features

**Search & Investigate**
- Search by IP (full or partial), CIDR range (e.g. `185.220.0.0/16`), or paste multiple IPs for bulk check
- Advanced filters: date range, role, country, ASN, hostname, port — all combinable
- Per-IP activity timeline with drag-to-zoom and adaptive time markers
- /24 subnet neighbors and same-ASN peers for infrastructure attribution
- Shareable URLs for any search — click an IP to copy its direct link

**Changes Feed**
- New nodes, gone nodes, long-running relays, and role changes
- Period toggles: 24h, 7 days, 30 days, 3 months, 6 months, 1 year

**Download Dataset**
- Filter by time period (presets or custom range) and node type (exit, guard, middle)
- Export formats: CSV with full metadata, JSON with full metadata, IPs-only in .txt / .csv / .json

**Intelligence Panels**
- Top 20 autonomous systems hosting TOR nodes
- Top 20 /24 subnets and top 15 /16 ranges by node density
- Active vs inactive node counts, role distribution with percentages


## License

Part of [mthcht/awesome-lists](https://github.com/mthcht/awesome-lists). See repository license.
