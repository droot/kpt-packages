# new-bp

## Description
test blueprint

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] new-bp`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree new-bp`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init new-bp
kpt live apply new-bp --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
