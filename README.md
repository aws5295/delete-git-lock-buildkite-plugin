Delete Git Lock Buildkite Plugin
===============================

A [Buildkite plugin](https://buildkite.com/docs/agent/plugins) to delete the git lock on the repository.  Use with caution.

Example
-------


```yaml
steps:
  - command: bin/some-command
    plugins:
      aws5295/delete-git-lock: ~
```

Options
-------

None

License
-------

MIT (see [LICENSE](LICENSE))
