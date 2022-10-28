# mono-clone

A fast way to clone monorepo shallowly

> A simple alternative for `scalar clone` ([Scalar](https://devblogs.microsoft.com/devops/introducing-scalar/) )

## Usage

```bash
npx mono-clone YOUR_REPO_URL
```

What does it do?

- [x] Enable [partial-clone](https://git-scm.com/docs/partial-clone) and [sparse-checkout](https://github.blog/2020-01-17-bring-your-monorepo-down-to-size-with-sparse-checkout/)
- [x] Start [git-maintenance](https://git-scm.com/docs/git-maintenance)
- [ ] Be workspace-wise

## Why

Users have to [use the Microsoft fork of Git](https://github.com/microsoft/scalar#scalar-has-moved) if they want the latest version of Scalar which may be inconvenient.
