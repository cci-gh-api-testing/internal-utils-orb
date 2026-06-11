# internal-utils-orb

Private test orb for CircleCI org migration testing.

## Usage

```yaml
orbs:
  utils: cci-gh-api-testing/internal-utils@0.0.1

workflows:
  example:
    jobs:
      - utils/internal-test
```

## Publishing

Orb is published via CircleCI when a semver tag is pushed:

```bash
git tag v0.1.0
git push origin v0.1.0
```
