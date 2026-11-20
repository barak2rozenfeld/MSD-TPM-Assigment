# MSD TPM Assignment — Next-Generation Embedded Server

A self-contained HTML proposal for taking the Advanced Monitoring on-prem farm
server to its next generation, migrating the SOM from **LEC-iMX6** to
**LEC-iMX95** (SMARC / ADLINK). The device is an IP67 gateway and on-prem
server whose server, database and web app stay fully functional on the farm
even with no cloud connection.

Author: **Barak Rozenfeld** (TPM Assignment, MSD Animal Health)

## Contents
- **`index.html`** — the business deck (4 slides, offline-capable, single file).
  Open it directly in any modern browser, or use the in-page **Download PDF**
  button to export.
- **`assets/`** — logo and device photo.

## The four slides
1. **Launch decision** — run the i.MX95 server with the same offline farm workflows.
2. **Three reasons** — secure long-term supply, headroom to grow, security for the long term.
3. **Minimum change** — the carrier and enclosure delta, the R&D and NPI work, and an offline acceptance test.
4. **Timeline** — 12 milestones (about 10 months) with two parallel tracks and three de-risking proofs.

## Viewing online
Everything is embedded in `index.html` (styles, scripts and images), so it
works offline. To serve it online, enable GitHub Pages (branch `main`, root).
