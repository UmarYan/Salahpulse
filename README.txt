SalahPulse V9.0 — Revamped Stable

Built from the stable V8.8.1 / V8.7 UI base with the approved revamp.

Changes:
- Fixed the V8.9 blank-screen regression: complete settings/menu markup is preserved, startup does not hide the app, and a visible recovery message appears if rendering fails.
- PWA service worker uses a new cache namespace and network-first navigation so deployed updates reach the installed app.
- Home summary: meaningful fulfilled-Salah breakdown replaces “Prayers recorded”.
- Prayer Times includes the next Salah.
- Stats Review period is at the top and controls the period-based metrics below.
- Stats fulfillment clearly separates performed, Qaza, Missed and not-recorded.
- Prominent Current streak / Best streak / Full-day gamification metrics removed.
- Stats consolidated: fulfillment, consistency strength, Timeliness, Jama’ah, Each Salah, selected-period pattern, consistency trend, Salah by day and recent days.
- Duplicate Why & Improve card removed from Stats; Reasons remains its own section.
- Reasons period selector correctly follows the selected period.
- Pending Qaza remains separate from the original Missed record.
- Old Reflection & Intention and old manual Qaza Log are not restored.
- Existing localStorage key remains salahpulse_v7 for data continuity.

Deploy all 7 files to GitHub Pages.
