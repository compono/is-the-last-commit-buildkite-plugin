# IS THE COMMIT THE LAST COMMIT IN THE BRANCH?

```
steps:
  - label: "Run something"
    commands: "do_something"
    plugins:
      - https://github.com/runlevel5/is-the-last-commit-buildkite-plugin.git: ~
```

If the `BUILDKITE_COMMIT` is not the last commit of `BUILDKITE_BRANCH`, the plugin would `exit 1`