# Contributing

## Branch Strategy
- `main`: production-ready, stable history only.
- `develop`: integration branch for completed features and fixes.
- `feature/*`: new feature work branched from `develop`.
- `fix/*`: bug fixes branched from `develop`.

## Workflow
1. Create a branch from `develop`:
   - `feature/<short-name>` or `fix/<short-name>`
2. Make commits and push your branch.
3. Open a Pull Request into `develop`.
4. After review and validation, merge into `develop`.
5. Promote to `main` when ready for release.
