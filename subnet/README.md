# subnet

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] subnet`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree subnet`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init subnet
kpt live apply subnet --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
