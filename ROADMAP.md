# Roadmap / Výhled vývoje

This is a **directional roadmap**, not a release schedule. Priorities can change based on testing.

## Phase 1 — Read-only network visibility
- [x] Native Windows snapshot monitor for TCP and local UDP endpoints.
- [x] Basic process association and interactive connection table.
- [x] Initial GUI and localization.
- [ ] Further visual and usability refinement.

## Phase 2 — More complete network activity
- [x] Investigate ETW-based event monitoring in isolated prototypes.
- [ ] Integrate a reliable event-monitoring service into the application.
- [ ] Handle permissions, recovery, bounded queues and resource limits safely.
- [ ] Add clearly sourced historical information.

## Phase 3 — User-directed control
- [ ] Independent filtering/blocking implementation with safe defaults and rollback.
- [ ] Rules for applications, connections and addresses.
- [ ] Reliable observations and statistics for blocked traffic.
- [ ] Intrusion Watch overview and opt-in IP information lookup.

## Phase 4 — Public testing and release
- [ ] Security, privacy and performance review.
- [ ] Finalize licensing and release terms.
- [ ] Public testing and distribution, when ready.

No public download or release date is available yet.
