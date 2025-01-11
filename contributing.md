# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test skopeo https://github.com/zdzielinski/asdf-skopeo.git "skopeo --version"
```

Tests are automatically run in GitHub Actions on push and PR.
