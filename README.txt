SalahPulse V8.8.1 — Stable Rollback

This is a stability-first rollback to the last known working Qaza redesign before the V8.9 Stats changes.

Included:
- Prayers and existing Salah status tracking
- Reasons & Improve
- Pending Qaza: Missed → Pending Qaza → Mark Qaza Done
- Original Missed record remains unchanged after Qaza completion
- Old manual Qaza log and Reflection & Intention remain removed

Stability fix:
- PWA service-worker cache version bumped to force a clean update after rollback.

Do not apply the planned Stats revamp yet; it will be added only after this stable version is confirmed working.
