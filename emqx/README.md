# emqx

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] emqx`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree emqx`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init emqx
kpt live apply emqx --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
