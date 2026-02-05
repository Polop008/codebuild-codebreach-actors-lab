# CodeBuild CodeBreach Actors Lab

Intentionally vulnerable training repository for AWS CodeBuild webhook filter misconfigurations.

- Path A: `ACTOR_ACCOUNT_ID` weak regex (`0|1`) on `PULL_REQUEST_CREATED`
- Path B: weak second `filterGroup` on `PULL_REQUEST_UPDATED`

## Safety note
This repository is for training only.
path-b-trigger 2026-02-05T15:26:18Z
