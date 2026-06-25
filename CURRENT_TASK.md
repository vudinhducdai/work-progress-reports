# CURRENT TASK - GateKeeper ERP

**Cap nhat:** 25/06/2026 07:35
**Branch:** main
**Repo:** github.com/vudinhducdai/erp

## Da hoan thanh (session nay)
- feat(audit): Enterprise audit log — risk scoring, traceId, actor snapshot, diff, SSE, CSV export, integrity verify
- fix(security): Mask SMTP pass/token trong GET /api/settings; admin-only cho key nhay cam
- fix(security): Settings cache thundering herd — refreshPromise pattern
- fix(security): authOptional gio check blacklist + force-logout
- fix(ui): Search icon SVG sau input trong DOM (settings, departments pages)

## Commit gan nhat
- `59cfc42` fix(security): mask sensitive settings, admin-only keys, settings cache
- `1a7ec42` feat(audit): enterprise-grade audit log system (9 files, +803 lines)
- `f1ce345` fix(ui): search icon DOM order fix

## Pipeline
TS [OK] | Tests 13/13 [OK] | Lint [OK]
