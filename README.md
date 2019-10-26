# Swift Orb [![CircleCI Build Status](https://circleci.com/gh/CircleCI-Public/swift-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/CircleCI-Public/swift-orb) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/CircleCI-Public/swift-orb/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

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
