QuarantineCare v2 (static prototype)
Deploy: put index.html at repo root, import to Vercel, framework preset "Other", no build command.
Open the live link, pick a role in the header ("Demo login"), and use "Reset demo data" to restore the 74-bed sample.
Demo flow: Admin admits a patient (or waitlists when full) -> Nurse records temperature -> Doctor completes visit (or emergency visit) -> Admin discharges eligible patient -> Manager sees mortality/recovery with period filter.
Limits: browser-local data, no real authentication or server-side permissions. Fever threshold (38.0C) and the "3 consecutive calendar days with documented readings" rule are demo assumptions for the medical owner to confirm.
