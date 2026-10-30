# IPL repository consolidation plan

This document records the planned non-destructive consolidation of two repositories owned by TrungHieu02.

- Source repositories: `TrungHieu02/IPL_Job` and `TrungHieu02/IPL_JobRecSys`.
- At the time of inspection (2026-10-30), `IPL_Job` was empty on GitHub; `IPL_JobRecSys` held the existing code and Git history.
- Consolidation target: one repository, with the recommender code in its own directory. Preserve the existing commit history by moving files in a new commit, without rewriting previous commits.
- Avoid changing `main` until the resulting layout has been reviewed.
- Do not delete or archive either original repository as part of the initial consolidation.
