# macvlan

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] macvlan`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree macvlan`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init macvlan
kpt live apply macvlan --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
