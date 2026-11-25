# CzechMyNet — Development Roadmap

**Your network. Your rules.**

This is a record of **completed development milestones and future work**.
Completed prototypes are not claims that production features are ready.
No public release or download date is promised.

## Completed so far

- [x] **Stage 0 — Architecture and foundation.** Native Windows/C++ codebase,
  CMake build, basic tests, Czech and English resources, local-first and
  low-resource design rules.
- [x] **Stage 1 — Read-only network monitor.** TCP IPv4/IPv6 snapshots, local
  UDP endpoints, available process/PID details, filtering, sorting and refresh.
  This never claimed to capture all short-lived connections or packet counts.
- [x] **Stage 2 — Event-stream research and test prototypes.** Isolated ETW
  proof of concept plus Helper/IPC/watchdog and controlled recovery tests.
  **Production integration remains unfinished.**
- [x] **Stage 3A — Working Advanced GUI foundation.** Native Dashboard,
  initial Connections/details view, Czech/English UI, theme switching,
  monitored aggregates and original cyberpunk styling.
  Accessibility/performance release gates remain open.

## Planned next — functionality first

- [ ] **Stage 3B — Complete Connections page.** A genuinely usable second
  screen listing observed connections and app owners, with filters, sorting,
  details, timestamps and clear source/accuracy limitations.
- [ ] **Stage 4 — User-controlled blocking.** Independent reversible filters
  without changing Microsoft Defender Firewall rule configuration; safe
  permissions, reliable blocked-attempt evidence and failure recovery.
- [ ] **Stage 5 — Safe test mode.** Temporary rules, expiry, easy rollback
  and checks for unexpected effects on normal applications.
- [ ] **Stage 6 — Unsuitable-connection information.** Optional free sources
  for known threats, trackers/advertising/telemetry and neutral context about
  companies or institutions. An **unwanted** connection is not necessarily
  **malicious**. No blanket bans against Microsoft, Google, Meta or government
  infrastructure. Explicit opt-in, source/freshness/license details and
  shared-IP safeguards.
- [ ] **Stage 7 — Conservative Easy Mode.** A simple two-dial dashboard:
  **incoming on the left**, **outgoing on the right**. When reliable counters
  exist, the main needle shows total activity, a lower needle plus red sector
  shows blocked activity, and green between them shows allowed activity.
  Clear units/time window, simple explanations and undo; no aggressive silent
  default blocking.
- [ ] **Stage 8 — Public beta.** Complete verification of functionality,
  safety, performance, accessibility, licenses, installer and documentation.

## Stručně česky

### Už proběhlo
- [x] Architektura a technický základ Windows aplikace.
- [x] První funkční monitor TCP/UDP spojení v režimu pouze pro čtení.
- [x] Výzkum a ověřené izolované experimenty s ETW.
- [x] Základní Advanced GUI a cyberpunkový vzhled.

### Co bude dál
- [ ] Dokončit skutečně funkční druhou stránku s výpisem spojení.
- [ ] Vytvořit bezpečné a vratné blokování.
- [ ] Přidat zkušební režim blokací.
- [ ] Zapojit volitelné databáze **nevhodných spojení** se zdroji a ověřením.
- [ ] Připravit konzervativní Easy Mode se dvěma budíky.
- [ ] Po důkladných testech nabídnout veřejnou betu.

> CzechMyNet doesn't decide what you should trust. It gives you the
> information and tools to decide for yourself.
