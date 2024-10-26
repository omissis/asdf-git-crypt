# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test git-crypt https://github.com/omissis/asdf-git-crypt.git "git-crypt --help"
```

Tests are automatically run in GitHub Actions on push and PR.
