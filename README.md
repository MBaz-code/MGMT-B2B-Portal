# Snoonu B2B — Integrated Logistics Portal (Demo)

A fully working, single-file demo of a B2B last-mile logistics portal for Snoonu's
proposed Qatar B2B expansion (SMEs, corporates, cafés/restaurants, and government clients).

> Built for the MGMT4000 *Snoonu B2B Business Model Integration* strategic plan.
> Snoonu-inspired purple/blue styling — no official brand assets used.

## Run it

Just open **`index.html`** in any modern browser. No build step, no server, no
dependencies — everything (HTML, CSS, JavaScript) lives in the one file.

## What's inside

| Area | Highlights |
|------|-----------|
| **Dashboard** | KPI cards (active deliveries, on-time rate, open invoices, retention) |
| **Live Tracking** | Doha-style map with routes and **moving vehicle markers** (JS-simulated, real-time) |
| **Orders** | Delivery cards with order ID, client, route, status, ETA & progress bar; click to open detail panel |
| **Order detail** | Driver, current street / pickup / drop-off, and a 6-step timeline (created → assigned → picked up → in transit → delivered → invoice updated) |
| **SLA Reports** | On-time rate, complaint rate, avg response time, retention, trend chart, per-client table |
| **Invoices** | Monthly delivery, white-label, bulk fulfilment & restocking fees + total open amount |
| **Service Packages** | Usage-based pricing — Starter / Business / Enterprise monthly plans with an included delivery allowance, then **pay-per-use overage** beyond the limit, plus a live usage meter & cost simulator |
| **Account Manager** | Client-success support promise & SLA package |

## Interactive features

- **➕ New B2B Delivery** — dispatches a new order that immediately starts moving on the map
- **⬇️ Export SLA Report (CSV)** — generates and downloads a real CSV file
- **🔗 Copy tracking link** — copies a demo client tracking URL to the clipboard
- **Filters & search** — by delivery status and by client / order ID
- Fully **responsive** for desktop and mobile (collapsing sidebar drawer)

*All data is simulated for demonstration purposes.*

## Live site & QR code

The portal is hosted on **GitHub Pages** (reliable on phone, tablet and laptop —
unlike the htmlpreview proxy, which is flaky on mobile):

```
https://mbaz-code.github.io/MGMT-B2B-Portal/
```

### One-time setup to turn the live site on
GitHub only lets a repo **admin** enable Pages, so this has to be done once in the UI:

1. Repo → **Settings** → **Pages**
2. **Build and deployment → Source → "Deploy from a branch"**
3. Branch: **`claude/hopeful-johnson-mh7hfi`** · folder: **`/ (root)`** → **Save**
4. Wait ~1 minute, then open the URL above. Every future push auto-rebuilds it.

### QR codes (point at the live site above)

| File | Use |
|------|-----|
| `assets/snoonu-b2b-qr-card.png` | Branded, presentation-ready card (Snoonu purple) — drop straight into slides |
| `assets/snoonu-b2b-qr.png` | Plain high-contrast QR (most universally scannable) |
| `assets/snoonu-b2b-qr.svg` | Vector version — scales to any size for print |

> Error-correction level **H** (~30% damage tolerance), QR version 5 — compact and
> easy to scan from a projected slide. Both PNGs are verified to decode to the URL.

