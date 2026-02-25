# Patient Management — Draft UI (Bootstrap)

A simple **UI portfolio mock** for a **Patient Management** dashboard.  
Built as a **single static HTML file** using **Bootstrap 5** with a **white / blue / red** palette and a **draft / wireframe look** (dashed borders, placeholders, skeleton bars, “DRAFT” labels).

> ✅ UI-only demo — **no backend**, **no real patient data**, no authentication.

---

## Preview

What’s included:

- Sticky top bar (clinic + date + draft notes)
- Patient list table (search, filter, sort)
- Quick filter chips (appointments, risk, labs, unread messages)
- Right-side patient preview panel (wireframe placeholder + skeleton text)
- Draft widgets: today’s appointments + alerts
- Bootstrap modals:
  - New patient (draft form)
  - Create alert
  - Quick actions: schedule, message, labs, discharge
  - Draft notes

---

## Tech

- **HTML + CSS + Vanilla JS**
- **Bootstrap 5** via CDN
- No build tools, no dependencies

---

## Getting Started

1. Create a file named `index.html`
2. Paste the provided HTML into it
3. Open `index.html` in your browser

Optional: serve locally (recommended for testing)

```bash
# Python
python -m http.server 8080
