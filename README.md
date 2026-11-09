# Voipho CRM
Static Voipho CRM. Statuses sync via the same Firebase RTDB as Klober (voipho/main).

## iPhone share (2026-11-09)
- `Voipho-CRM.shortcut` (signed): Share → Voipho CRM. Links open `?add=<url>`; images/PDF/files are POSTed to Firebase `voipho-inbox/main` and the page opens with `?inbox=1`, which turns them into manual leads (attachments in `voipho-files/main/<leadId>`).
- Shared leads sync via the synced key `voipho-crm-shared-leads-v1`.
- `manifest.json` + `apple-touch-icon.png` make "Add to Home Screen" open Voipho as its own app.
