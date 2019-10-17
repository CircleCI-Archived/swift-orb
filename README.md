# Swift Orb

CircleCI Orb for linting Swift projects. More information about CircleCI Orbs can be found [here](https://circleci.com/orbs/)

## Usage

See below for a simple implementation of this orb's `build-and-test` job

### Simple

```yaml
description: |
  This orb can help you lint your Swift projects, storing output
  as CircleCI artifacts and test results
usage:
  version: 2.1

  orbs:
    swift: circleci/swift@1.0.0

  workflows:
    build-and-test:
      jobs:
        - swift/lint
```
