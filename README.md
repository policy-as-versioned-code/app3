# App3

> This app is compliant with version [2.1.1](https://github.com/policy-as-versioned-code/policy/releases/tag/2.1.1) of the company policy

## Test policy locally

```raw
$ docker run --rm -ti -v $(pwd):/apps ghcr.io/policy-as-versioned-code/policy-checker
Found kustomization.yaml
Checking policy version...
Policy version: 2.1.1
Fetching Policy...
Policy fetched.
Running policy checker...

Applying 2 policies to 1 resource...
(Total number of result count may vary as the policy is mutated by Kyverno. To check the mutated policy please try with log level 5)

pass: 2, fail: 0, warn: 0, error: 0, skip: 0
```