# CURRENT TASK - GateKeeper ERP

**Cap nhat:** 25/06/2026 12:45
**Branch:** main
**Repo:** github.com/vudinhducdai/erp

## Da hoan thanh (session nay)
- fix(#24): employeeCode CSPRNG — crypto.randomBytes instead of Math.random()
- fix(#19): createEmployee race condition — wrap in transaction
- fix(#21): updateEmployee identityNumber clear — properly clear hash
- fix(#22): updateProfile CCCD duplicate check — validate before update
- fix(#20): managedDepartmentIds empty — recursive department query
- fix(#18): avatarPath traversal — validate path
- fix(#23): listEndpoints hardcoded — /api/system/list-endpoints API

## Commit gan nhat
- `513575a` fix: resolve 7 security & data consistency issues

## Pipeline
TS [OK] | Tests 13/13 [OK] | Lint [OK]
