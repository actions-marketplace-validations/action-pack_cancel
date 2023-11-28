<h1 align="center">Cancel Workflow<br />
<div align="center">
  
  [![Build](https://github.com/action-pack/cancel-action/workflows/Build/badge.svg)](https://github.com/action-pack/cancel-action/)
  [![Version](https://img.shields.io/github/v/tag/action-pack/cancel-action?label=version&sort=semver&color=066da5)](https://github.com/marketplace/actions/cancel-workflow)
  [![Size](https://img.shields.io/github/languages/code-size/action-pack/cancel-action?label=size&color=066da5)](https://github.com/action-pack/cancel-action/)
  
</div></h1>

This action cancels the currently running workflow.

## Usage

```yaml
permissions:
      actions: write

    steps:
      - name: Cancelling workflow
        uses: action-pack/cancel-action@v1
```

In combination with the ```if``` statement, this allows you to cancel the workflow conditionally.
