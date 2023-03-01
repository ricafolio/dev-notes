# Git simplified naming convention
- Designed for solo developer

## Branch
- `feat/name-here` - for adding, refactoring or removing a feature
- `bugfix/name-here` - for fixing a bug
- `hotfix/name-here` - for changing code with a temporary solution and/or without following the usual process (usually because of an emergency)
- `test/name-here` - for experimenting outside of an issue/ticket

## Commits
- `feat: desc here` - for adding a new feature
- `fix: desc here` - for fixing a bug
- `refactor: desc here` - for changing code for peformance or convenience purpose (e.g. readibility)
- `chore: desc here` - for everything else (writing documentation, formatting, adding tests, cleaning useless code etc.)

### Commit description
- should start with a verb conjugated in an imperative way
- should be seperated from themselves with a ";"
```
git commit -m '<category: do something; do some other things>'
```

### Sample verbs
- `add` = Create a capability e.g. feature, test, dependency.
- `cut` = Remove a capability e.g. feature, test, dependency.
- `fix` = Fix an issue e.g. bug, typo, accident, misstatement.
- `bump` = Increase the version of something e.g. dependency.
- `make` = Change the build process, or tooling, or infra.
- `start` = Begin doing something; e.g. create a feature flag.
- `stop` = End doing something; e.g. remove a feature flag.
- `refactor` = A code change that MUST be just a refactoring.
- `reformat` = Refactor of formatting, e.g. omit whitespace.
- `optimise` = Refactor of performance, e.g. speed up code.
- `document` = Refactor of documentation, e.g. help files.

### Credits
- https://dev.to/varbsan/a-simplified-convention-for-naming-branches-and-commits-in-git-il4
- https://dev.to/couchcamote/git-branching-name-convention-cch
- https://github.com/knowbl/git-commit-message
