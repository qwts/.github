# qwts/.github — org-wide defaults

Default community health files for all `qwts` repositories, per
[ENG-0008](https://github.com/qwts/playbook-engineering/blob/master/docs/decisions/ENG-0008-shared-sop-inheritance.md)
(shared baselines, inherited by default, varied only by explicit delta).

GitHub serves these files to any `qwts` repo that does not carry its own:

- `SECURITY.md` — vulnerability reporting for every repo
- `SUPPORT.md` — where to ask questions
- `PULL_REQUEST_TEMPLATE.md` — default PR structure

A repo that needs a variation adds its own file (the delta model); it does
not edit these defaults. The canonical baseline-file list lives in the
playbook: `docs/sop/repo-baseline-files.md`.
