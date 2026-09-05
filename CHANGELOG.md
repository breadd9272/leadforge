# Changelog

All notable changes to LeadForge are documented here.

## v1.0.16 — 2026-08-30

Portable release.

### Added
- Instant **Stop** on scans — no confirmation popup, all leads found so far are kept
- **Restart** button on stopped/paused/failed runs (reuses the stored queries)
- Amber "stopped/paused" status pill on history cards

### Improved
- Honest run recovery after app/machine restarts — interrupted scans are marked correctly instead of faking "completed"
- Stability fixes in the contact extraction stage

---

## v1.0.15 — 2026-08-30

Portable release.

### Added
- Stop & delete run — start a brand-new scan immediately after stopping
- Restart from history with one click

---

## v1.0.14 — 2026-08-29

Portable release.

### Fixed
- Mailbox connection flow (app-password guide, verification fallback between SSL/STARTTLS)

---

## v1.0.0 — 2026-08-23

First public portable release.

- 5-stage discovery pipeline (YouTube Search → Channel Details → Video Fetch → Contact Extraction → Lead Analysis)
- Leads table with 17 columns, filters, Excel/CSV export
- Cold-email campaigns with merge tags, InboxGuard scoring, per-mailbox daily limits
- Chrome extension companion
