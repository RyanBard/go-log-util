# go-log-util

Common logging functions for slog used in multiple microservices, etc. to use consistent context keys and structured logging fields

## Formatting, Building, etc.

```
make
```

## Generating Coverage Report

```
make coverage-html
open _coverage/coverage.html
```

## Publishing Changes

```
git push origin master
git tag v0.0.0 # supply the correct semantic version
git push origin v0.0.0
```
