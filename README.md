# changedetection-v0.53.6 - 漏洞总览

| Title | Endpoint |
|---|---|
| CVE-2026-27645 — Reflected XSS (CWE-79) | `GET /rss/watch/<uuid>` |
| CVE-2026-27696 — Server-Side Request Forgery (CWE-918) | `POST /api/v1/watch` (url) |
| CVE-2026-29038 — Reflected XSS (CWE-79) | `GET /rss/tag/<tag_uuid>` |
| CVE-2026-29039 — Arbitrary File Read via XPath (CWE-94) | `include_filters` (`xpath:unparsed-text`) |
| CVE-2026-29065 — Zip Slip Path Traversal (CWE-22) | `POST /backups/restore/start` |
| CVE-2026-33981 — Environment Variable Exposure via jq `env` (CWE-200) | `include_filters` (`jq:`/`jqraw:`) |
| CVE-2026-35490 — Authentication Bypass via decorator ordering (CWE-863) | 13 routes across 5 blueprints |
