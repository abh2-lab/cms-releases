## 1.1.0 — 2026-08-25

Update detection. Your install now knows its own version, checks once a day for
a newer one, and shows a banner when an update is available. Nothing is applied
automatically.

**This release adds a database table** (`update_status`). The migration runs by
itself when the containers restart. It only adds a new table — nothing existing
is changed — so it is safe.



# CMS releases

## 1.0.0 — 2026-08-25

First released version. Baseline for the update system.
