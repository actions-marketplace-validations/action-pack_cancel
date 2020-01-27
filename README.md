This Action uses the GitHub API to cancel the workflow. Example usage:

```
    - name: cancelling
      uses: andymckay/cancel-action@master
      with:
        token: ${{ github.token }}
        repository: ${{ github.repository }}
```

The cancellation might take a few seconds to process, this is most useful when you'd like to cancel a long running build. In combination with the `if` statement, this allows you to cancel the build conditionally.