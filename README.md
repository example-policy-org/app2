# App2

> This app is compliant with version [2.0.1](https://github.com/example-policy-org/policy/releases/tag/2.0.1) of the company policy 

## Test policy locally

```bash
$ docker run --rm -ti -v $(pwd):/apps ghcr.io/example-policy-org/policy-checker

Checking policy version...
Policy version: 2.0.0
Fetching Policy...

Applying 2 policies to 1 resource...
(Total number of result count may vary as the policy is mutated by Kyverno. To check the mutated policy please try with log level 5)

pass: 2, fail: 0, warn: 0, error: 0, skip: 0
```
